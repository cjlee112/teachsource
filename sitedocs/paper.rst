#########################################################################
TeachPub.Org: An Open Source Bioinformatics Teaching Materials Consortium
#########################################################################

:Authors: C. Lee, M. Levitt, M. Pellegrini, I. Yanai, G. Yona

Introduction
------------

Many commentators have argued that
the Internet age brings opportunities to improve the efficiency
and effectiveness of education.  
For our part, we think it striking that higher education
is rife with inefficiencies that would not be tolerated in
research.  For example, in research one does not receive credit
simply for developing something, but only when it is shared
(published) so that all others can use it.  Moreover, research funding
abhors "re-inventing the wheel"; hence researchers focus their
contributions on *innovations*, and areas where they have 
special expertise.  By contrast, when a new faculty member
starts teaching, it is mostly taken for granted that s/he must undertake
the enormous effort of generating lecture
materials, exercises, and tests.  (Simply reusing someone
else's materials might even be viewed as a form of "cheating").
When one considers that very similar course content has been
taught many times over not only at other universities but even 
with the same department, 
this is re-inventing the wheel with a vengeance.
This gross discrepancy between research vs. teaching
reflects clear institutional priorities: success in research
is paramount (and hence is at least organized as a rational and
competitive market), whereas the efficacy of the university 
teaching enterprise ... is not even measured.

Recently, Massive Open Online Courses (MOOCs) have excited much
attention as the prime contender for a new, more efficient model
of education.  MOOCs use technology (effectively, a web server for
materials distribution and student interaction, and YouTube-style video for 
delivering lectures) to increase the number of students who
can take a single course to 100,000 or more.  In this paradigm,
efficiency is to be attained by letting students converge to the
very "best" teacher in the world for a given topic, obviating
the need for many other teachers who are offering
similar (but presumably inferior) versions.  Leaving aside
questions about the actual learning efficacy of MOOCs, many 
commentators seem to think that higher education will undergo
such a consolidation as an almost inevitable consequence of
its current inefficiency.

And yet.  There might be other efficient models.  We note two
fundamental discrepancies between MOOCs and established models
for efficient information networks.  First, MOOCs are incompatible with
the principles of *publication* that prevail in research.
The purpose of publication is reuse -- to enable everyone to
use a beneficial development (and to secure credit to its
developer).  By contrast, MOOCs explicitly block reuse; Coursera,
for example, treats materials provided to Coursera (by university
professors) as its intellectual property, and forbids reuse by
others.  This makes sense: a MOOC must compete for a dominant
share of its "market", so it can't afford to give away its
competitive advantages to competitors.
Second, this also renders MOOCs incompatible with the
*open source* model, whose entire purpose is to enable everyone
to do *everything* with an invention that the original creator
could conceivably do (by contrast, in a closed-source model
the invention is only made available with specific, limited
capabilities that cannot be extended).

These established models (publication, and open source) 
are often overlooked not only by
outside commentators, but even by institutional efforts to
improve the efficiency of education.  For example, it is 
ironic that the OpenCourseWare consortium actually 
distributes *closed-source* materials (PDF format, which
is designed to permit viewing only).  That is, while OpenCourseWare
explicitly allows free reuse in its legal license
(Creative Commons Attribution 3.0), that freedom is
severely constrained in practice by distributing a *non-editable*
format.  OpenCourseWare users *cannot* do everything with the
materials that the original author could do, precisely because
the *source files* that enable the author to make whatever changes they
want (e.g. Powerpoint file for a lecture) have been *withheld*.
By definition that is closed-source, not open-source.
The very existence of such a self-contradictory
policy, and its apparent lack of controversy in the education
field, suggest that this field does not really understand
or appreciate the concept of "open source".

Does this matter?  After all, as long as all *students* are
able to access a MOOC, what does it matter if others are blocked
from reusing it?  Let's translate that into software
terms: "as long as *consumers* are able to use Microsoft Windows,
what does it matter that no one (but Microsoft) can see or 
re-compile source code for the operating system everyone relies on?"
This question has been decisively answered by decades of 
experience with closed-source vs. open-source software.
This is a choice between fundamentally different kinds of economies:
an economy of monopoly vs. an economy of reuse.
The reason that publication and open-source have won in
their respective domains is that they are dramatically
more efficient, because they enable the most important type
of reuse: *combining* multiple elements from different
sources, for *purposes* other than that implemented by
the original author, by *people* other than the original author.
This is the difference between what one person or group ("the owner")
can do with an idea, versus what the whole world can do.
We will distinguish such different levels of reuse as
*verbatim reuse* (using an identical copy of a distributed material), 
*remixing*, *re-purposing*, and *unified collaboration* 
(multiple people contributing improvements to the same material).
 
We wish to propose a consortium for open source teaching 
materials in bioinformatics, based on the following principles:

* *teaching as publication*: contributing teaching materials
  should be treated as a form of publication.  Specifically,
  we wish to establish an "open market" where teaching materials
  are published, and users can search for and use them.
  Contributed teaching materials are automatically peer reviewed 
  and tracked for impact like any publication: that is, other instructors' 
  choosing to reuse those materials constitutes peer review and 
  also  tracks impact (e.g. total number of students using those materials).
* *open source standards*: teaching materials should be
  published as open-source standard formats (e.g. text) rather than
  closed-source (e.g. PDF).  Materials should be annotated
  using a common standard (e.g. Wikipedia concept IDs) so
  all materials are interlinked by a common reference system.
* *open remix*: users should be able to easily find and combine
  pieces of many different materials (e.g. a single homework problem),
  along with their own materials, and "remix" them into whatever
  form they need (e.g. slides; PDF homework assignment; online
  exercises; an exam, etc.).
* *robust security options*: test questions are an essential category of
  teaching materials.  Contributors of assessment materials
  (e.g. exam problems) need to be able to choose an appropriate
  usage security policy (e.g. "final exam only": no distribution
  of the question, no exposure of the answer),
  and have assurance that only properly
  credentialed users (e.g. course instructors) can access their
  materials.
* *public online usage*: "self-study" is and has always been an important
  usage of textbooks, online course videos and other teaching materials.
  Therefore, all materials not specifically reserved for assessment will
  be public.

This could have several benefits, both for students and faculty:

* *stop re-inventing the wheel, and start using the best
  available materials for each concept*:
  each instructor can draw on materials from a wide variety of
  experts, and thus can
  focus his contributions just on areas where he is expert.
* *easy adoption of active-learning materials*:
  in our experience, the exercises
  in a typical assigned textbook are far from adequate for students to 
  actually learn the desired concepts and skills.  Empirically,
  the existing publication channels have failed to give students the
  active-learning materials they need to "do the work" necessary
  for learning.  By contrast, open, online sharing of exercises
  seems like a natural way to bring together a huge collection
  of exercises for anyone's use.  Excellent examples include
  Project Euler (learn math through solving computational problems),
  and Rosalind (a similar resource for learning bioinformatics
  algorithms).  We have focused our initial repository of
  materials on exercises and a variety of active learning problems.
  TeachPub.org seeks to make it easy for an instructor to
  add an active learning component to an existing course
  (for example by asking a couple "concept test" questions per class),
  first by providing easy online tools for actually doing this
  (e.g. the Socraticqs In-Class Question System), and second
  by providing a large repository of active learning questions
  that anyone can use or contribute to.

We feel that materials sharing and remixing are especially
needed for a multidisciplinary field like bioinformatics, where we 
often need to integrate material and skills from several fields
(e.g. statistics and computer science) to teach a given bioinformatics
topic.  Unfortunately existing textbooks each tend to represent a
single kind of expertise (e.g. statistics) and thus is both
"too little" (lacks many other needed aspects) and "too much"
(assumes a lot of field-specific background and goals that
are actually not appropriate for your class).  What we often
need is the ability to remix exercises and materials from
a variety of partially overlapping courses; fully open-source
sharing is the natural way to do this.

Results
-------

We propose a teaching materials consortium, 
TeachPub.org, to address these needs.
Specifically, we have assembled a collection of online services
for reusing and remixing teaching materials from throughout the internet, 
and a repository of bioinformatics teaching materials designed
for easy reuse.  Anyone can try out these services now at
http://teachpub.org.

The TeachPub.org remix service
..............................

A core requirement for efficient sharing of teaching materials 
is the ability to *remix* any desired selection of elements
from all available materials on the internet.  This consists
of several basic capabilities:

* a ``SELECT`` mechanism that enables injection of desired
  content from any source into a composite output document.
  In effect the internet is treated as a database from which
  one can select in a variety of flexible ways (e.g. by 
  Wikipedia concept ID; by specified slides from a file; by OpenCourseWare
  course ID; by URL; by MongoDB query criteria, etc.).  Examples::


    .. select:: mongodb:
       * probability_def_slide format=slide
       * jointprob_def_slide format=slide
       * condprob_def_slide format=slide
       * disease_test_condprob format=multichoice_slide
       * venn_condprob format=ctslide
       * Chain_rule_probability.proof format=slide
       * (bullets=[Bayes'_theorem.derivation,Bayes'_theorem.comment.2]) format=bullet_slide
         :title: Bayes' Law
       * (bullets=[Normalization_statistics.definition,Normalization_statistics.comment]) format=bullet_slide
         :title: Normalization and Projection
       * (bullets=[Independence_probability_theory.formal-definition,Independence_probability_theory.comment]) format=bullet_slide
         :title: Statistical Independence

    .. select:: bigpresentation.pptx
       * pages=3-7

    .. select:: http://example.edu/bob/hw1.docx
       * pages=1,3-5

    .. select:: opencourseware:ID:lecture-notes/lec01.pdf
       * pages=1,2
       * pages=9-13
       * pages=5

* the ability to select from a variety of inputs: initially, TeachPub.org
  supports PDF, Microsoft Office, Open Office, and text format standards
  (LaTeX, reStructuredText and Sphinx, reUsableText extensions).  Since
  automated conversion utilities exist for most standard document
  formats, this can be easily extended.

* the ability to apply many desired layouts to the same content:
  e.g. Powerpoint style slides; "textbook chapter" formats;
  problemset or exam layouts (e.g. with appropriate space inserted
  for students to write their answers).  TeachPub.org uses 
  standard templating mechanisms to allow users to easily
  choose or customize layouts.

* the ability to automatically compile to many output file formats:
  initially, TeachPub.org can output PDF, web pages (HTML),
  and text format standards (LaTeX, reStructuredText).

* automatic tracking of credit for materials used.

The TeachPub.org teaching materials repository
..............................................

Founding members of TeachPub.org have contributed
an initial set of bioinformatics teaching materials 
covering a variety of topics ranging from probabilistic
models, sequence analysis, evolution, genomics and proteomics.
The initial repository consists of approximately 700
"units" (individual sections or problems; update this number
to include other members' material).  We have developed and
tested these materials over years of teaching such 
courses as: bioinformatics theory (for computer science students);
genomics and computational biology (for life science students)
(add other peoples' courses here).  The initial material
divides roughly as follows:

* *lecture materials*: given the diverse ways instructors present lectures
  (Powerpoint or its competitors; PDF slides; transparencies etc.),
  reuse-tools must work with a variety of input formats.  Fortunately,
  even (non-editable) PDF slides are valuable for this, because
  the tools can automatically remix individual or sets of slides from
  any PDF on the internet, combined with other sources.  We anticipate
  that online editing and sharing services like Google Docs / Google Drive
  will become an important component of reusing lecture materials
  on TeachPub.org.

* *problems, solutions and error models*:
  in our experience, the limited problems
  available in an assigned textbook for a course are often insufficient
  for students to learn the concepts and skills we're trying to teach.
  So we have focused on writing extensive collections of exercises
  that enable students to "do the work" necessary for learning.
  These include several distinct categories:

  * *skill problems*: these represent fairly traditional exercises
    where the student must solve a problem using one or more
    skills, e.g. derivations or computations.  Such problems 
    involve a significant amount of "mechanics" designed to
    exercise specific skills.

  * *conceptual problems*: so-called "concept tests" are designed
    to probe misunderstandings or misuses of a specific concept.
    They involve a minimum of mechanics; simply thinking about
    the problem conceptually should be enough to deduce the
    answer.  Many studies have shown that posing such questions
    in class (and on exams) leads to much greater student learning
    than simply lecturing.

  * *data analysis projects*

  * *algorithm problems*: we have not focused on this category because
    we feel the Rosalind project provides an excellent resource for
    this type of problems.

  In addition, the repository supplies *solutions* and *error models*
  for most problems.  Thus remixes of these materials can automatically
  generate solution keys.  Error models are a categorization of 
  distinct conceptual misunderstandings that students
  make on each of these problems, i.e. not the (surface) discrepancy
  vs. the correct answer, but its root cause.  These represent the
  key ways in which a class "loses" its students (i.e. they misunderstand
  an important aspect of a concept).

* *reading materials*: in our view, textbooks represent the strongest
  component of the traditional teaching materials landscape, and initially
  we have not focused on this.  

* *security*: graded (test) materials require security.
  Instructors won't contribute such materials unless they're
  assured that only authenticated instructors can access them,
  and will follow a specified access policy.  A contributor
  can specify one of the following access levels:

  * public: for teaching (rather than test) materials.
  * answer-restricted: the question but not the answer is public.
  * question-restricted: the material is only accessible to
    authenticated instructors.  
  * final-exam-only: instructors may only use in final exams,
    i.e. where no distribution of the question will ever occur,
    and no exposure of the answer.
  * private: only the contributor can access the question
    (presumably to remix it with other materials on TeachPub.org);
    later s/he may open it to other instructors.

  Instructors will be authenticated by logging in with the
  email address linked to their academic title by their
  university's directory.

* *public access*: All other users can access the public teaching materials, for
  self-study.

Why Open-Source Matters: the Case for Error Models
..................................................

In our view error models provide a good
example of how shared teaching materials can be better than
"private" teaching materials.  Textbooks simply do not 
undertake this kind of analysis.  Instructors likewise do not
see the wide range of error models on each concept unless
they actually run concept tests in every class session and
read all the student answers.  Even if they do, that information
is simply lost, i.e. it does not propagate to other
instructors.  Students themselves often don't
realize they've misunderstood, or cannot put a finger on exactly
where they went wrong (and hence cannot fix it).

By contrast, in a shared teaching materials repository,
faculty can each easily add error models they've observed
for a given question.  Not only will all users of that question
see these error models (and can address them in their teaching),
the Socraticqs in-class question system (see below) will automatically 
ask students answering this question whether they made any of
these known, common errors (and if they think they made a novel
error can flag their answer for further analysis by instructors).  
Identifying an individual student's error model could
be automatically linked to appropriate review and follow-up
exercises to correct the error, giving the student in effect
a custom tutorial tailored to their individual understanding.
Error models in TeachPub.org are derived from sample sizes
of 25 - 100 student answers per question.  Here is an example::

    :question: disease_test_condprob
      :title: Disease Test Question
      :tests: Disease_test_example
      A biotech company has developed a
      new test for a rare disease (found in less than 1% of the population),
      which predicts either that a patient has or
      does not have the disease.
      The company reports that in a random patient sample
      the test was 97% accurate (i.e. gave a negative test result)
      among patients who did not have the disease, 
      and 95% accurate (positive test result)
      among patients who actually had the disease.
      Choose the statement that best characterizes the test's reliability
      for a patient trying to interpret his test result.
      :multichoice:
        * The test reliably indicates whether the patient has disease or not.
        * The test does not reliably indicate whether the patient has
          disease or not.
        * The test's reliability depends on whether the test result is
          positive or negative. :correct:
        * The test's reliability depends on whether the patient
          has disease or not.
        * There's no way to know, based on this information.
      :answer:


        * This question asked you to assess the conditional probability
          :math:`p(D|T)`.  I.e. given the observation (the test result),
          what is the reliability vs. uncertainty in forecasting the hidden
          variable (whether the patient has disease).

        * Note that the question gave you the converse conditional probabilities
          :math:`p(T|D)`.  These are not relevant to a patient or doctor because
          they do not go from "what you know" (:math:`T`)
          to "what you want to know" (:math:`D`).

        * Estimating :math:`p(D^+|T^+)` follows straight from the stated numbers:
          :math:`p(D^+,T^+)<1\%`, and :math:`p(D^-, T^+)=3\%`, so
          :math:`p(D^+|T^+)<25\%`.  Not very reliable!
    
        * This problem of high false positive rate (because the actual disease
          is rare) is a very common problem in bioinformatics, where our calculations
          must "scale", e.g. to search for a single disease gene out of the 
          entire genome of 25,000 genes.

      :error:
        Many people didn't consider the *direction* of the conditional
        probability, even though the question's phrasing and answers encouraged
        you to do that.  (The question
        gave you :math:`p(O|H)` but asked you about :math:`p(H|O)`).
        Implies they didn't realize that any conditional
        probability has two possible directions.
      :error:
        In particular, people often forget to ask themselves which 
        direction is relevant in real life, i.e. which variable is
        *hidden* vs. *observable*.
        Suggestion: remember we can only make inferences (calculate
        probabilities) of things we want to know (*hidden*) based on
        things we know (observable).
        Etch into your minds: *Which variable is hidden? Which varible is
        observed?  Which direction of conditional probability am I being asked for?*
      :error:
        Etch into your minds: if a (hidden) state is rare, be very worried
        about the false positive rate (no matter how good the test is)!!
      :error:
        Some people chased red herrings like "does *reliable* mean 95%? 97%?"



Real-time Interaction via the Socraticqs In-Class Question System
.................................................................

When a user "remixes" a set of materials for a class, TeachPub.org
gives the option of automatically transferring "concept test"
questions from those materials to its In-Class Question System,
Socraticqs.  The instructor can then direct students
to login to the Socraticqs website during class and 
answer whatever question(s) s/he wishes, using their laptops
or smartphones.  This makes it easy to incorporate the
Socratic teaching method (active learning) into a class,
to whatever degree desired.  Furthermore, the TeachPub.org
repository includes a large selection of concept test questions
designed for this kind of in class exercises, enabling
instructors to add this "active learning" component to a class
with almost no effort (other than picking what questions
to use).  Socraticqs gives the instructor simple, real-time
control over exactly what to do vs. skip (from simply answering
a question to a full Peer Instruction discussion process), 
the ability to see student answers in real-time,
and self-evaluation by students against the correct answer
and common errors.

Open-source Software
....................

All components of TeachPub.org are open-source, some
developed specifically for this effort (teachpub,
socraticqs, reUsableText, relatex, rst2beamer equation
support).  It is also built
on strong foundations of many open source
packages, including Python, LaTeX, Sphinx, Git, MongoDB,
LibreOffice, MathJax, and many others.

Discussion
----------

To our minds, the choice between closed-source vs. open-source
models for education reflects differing assumptions about what
problem they're trying to solve.  Both MOOCs and OpenCourseWare
can be characterized as as
"free, closed-source": they make their materials available
for free, but in a read-only, closed-source form.
This presupposes that the only audience we are
trying to "open" the materials to is its *consumers*, i.e. 
students, who only need to be able to view, but not modify, remix etc.
This makes sense if we already know how teach a subject perfectly;
i.e. already have the ideal teaching materials in hand, and it's
simply a matter of improving the efficiency of the distribution
system (i.e. deliver them to massive numbers of students at very low cost).
It does *not* make sense if our teaching methods are ineffective
and our teaching materials are in need of a community overhaul.
Evidence from simple conceptual tests 
(such as the Force Concept Inventory)
indicate that courses even from the best universities
are startlingly ineffective (e.g. a year of Harvard intro physics
produced little improvement in Force Concept Inventory score).

Since the current crisis in education concerns not only 
issues of cost, but also basic failures of effectiveness and
methodology, the closed-source model seems highly inappropriate.
In our view, education now should be viewed as a *research* problem
requiring the concerted efforts of the whole community to 
discover, assess and share the most effective teaching methods
and materials.  And this should follow the same open publication
model that research follows, because that model makes
the difference between what one person or group ("the owner")
can do with an idea, versus what the whole world can do.

We briefly summarize a comparison of this open-source approach
with existing closed-source models (Table 1).  Note that not
all closed-source models are strictly MOOC; for example, 
OpenCourseWare, though closed-source in format (PDF), 
explicitly permits reuse in its legal licence (hence, all
OpenCourseWare materials can be automatically remixed
by TeachPub.org users).  One point which we wish to emphasize
is that, unlike MOOCs, our model is strictly agnostic about
online vs. traditional classroom instruction: it supports both
equally.  


.. list-table:: Table 1: Comparison of teaching scalability models
   :header-rows: 1

   * - Characteristic
     - MOOC (closed-source)
     - Open Source
   * - supports traditional classroom teaching?
     - No for Coursera; Yes for OpenCourseWare
     - Yes
   * - online access?
     - Yes
     - Yes
   * - scalability model
     - 100,000+ students can converge to "best course in the world"; courses compete for students
     - faculty can stop "reinventing the wheel" by sharing teaching materials
   * - legal license for reuse?
     - No for Coursera; Yes for OpenCourseWare
     - Yes
   * - format standards
     - closed-source (PDF + video)
     - open-source standards
   * - select & insert?
     - No
     - Yes
   * - remix to multiple layouts?
     - No
     - Yes
   * - user editable?
     - No
     - Yes
   * - secure sharing?
     - No
     - Yes
   * - peer reviewed?
     - No
     - Yes, automatically tracked
   * - citation metrics?
     - total student usage (but no reuse and hence no citation) for Coursera; No for OpenCourseWare
     - Yes, automatically tracked
   * - concept indexing?
     - No
     - Yes
   * - version control?
     - No
     - Yes
   * - unified collaboration?
     - No
     - Yes

It goes without saying that the initial version of TeachPub.org
is merely a prototype demonstrating the value and feasibility of
some of these principles, not a production service ready for users
to do all these things.  To assess these ideas more deeply, therefore,
it is useful to examine the most advanced open-source community, 
namely open-source software (OSS) development.  

First, this provides a reality check:
what is the actual value of remixing, re-purposing
and unified collaboration (as opposed to verbatim reuse alone)?  
In OSS, programmers take for granted
that an application can make use of *multiple* software libraries
(remixing), and that different applications can use a given library
to achieve quite different purposes (re-purposing).  So we can ask:
what fraction of applications depend on such remixing?
If we were to eliminate applications that depend 
on third-party OSS libraries, a large fraction of the world's software
would vanish (e.g. Google, Android, Mac OS X / iOS, Firefox, Apache
web server, Linux, etc.).  Second, OSS provides a model example of
the benefits of *unified collaboration*: GitHub, an OSS collaboration 
site ("social coding") with over 3 million members and 8 million
software projects.  Again, we can ask what fraction of popular
OSS applications depend on such collaboration for their development:
the vast majority (for the obvious reason that the task of developing
such an application is too big for one person or group, and benefits
greatly from contributions from outside experts).

To make this concrete, we will briefly sketch how the GitHub
unified collaboration model would work for teaching materials.
The first aspect is *distributed version control*, which not only records
the complete history of all versions of a given material and
their derivation from each other, but also can automatically
merge different users' changes  (into a single version that combines
everyone's contributions).  This "reunifies" their 
divergent efforts, which would otherwise fragment the material
into as many incompatible versions as it has users.  The second
required aspect is that this process be made easy and automatic:
e.g. every time an instructor makes a "product" (such as slides 
to show in class) out of a given material, the system automatically
saves a "snapshot" of whatever changes he's made vs. the material's
source.  It notifies the original author and asks whether to
automatically merge those changes back into the main version.
Note that such unification has major benefits
such as automatic peer review and impact tracking.

Let's consider the effect this would have on just
one aspect of teaching: error models.  Say one instructor
uses a problem in a class, and annotates the error models
observed in that class.  Any subsequent usage of this problem
will automatically ask students (during self-assessment)
whether they made any of those errors (and of course tracks
these statistics), and also highlights to their instructor
any *novel* errors.  Assuming the first set of error models
covers 80% of students, this reduces the next instructor's
effort by five-fold (he would only need to analyze the 20%
that made novel errors).  The instructor can devote time
instead to writing *remediations* (suggested review and 
exercises for students to overcome a specific error model).
As individual instructors contribute error models and
remediations, the problem gradually transforms from being
a one-shot "sink or swim" task (either you know it, or you don't),
to becoming a full tutorial that gives each student individualized
instruction, to identify their misconceptions about that
problem, and to do the work to overcome them.  At the same time
the system takes us from a sitation where progress is
practically impossible (because assembling such a vast array of
material for each problem is far too big for any one instructor),
to a situation where each person need only contribute a little
in order to accrue an enormous benefit from everyone else
(each instructor is now part of something much bigger than
himself).

We wish to suggest that universities should
welcome this teaching-as-publication model, first because
it can improve teaching and learning, and second because
it can reduce costs and improve efficiency.  Universities
should recognize that faculty have the right to publish
teaching materials (either via a traditional textbook
publisher or via TeachPub.org) just as they have a right
to publish research.

It goes without saying that our proposal only scratches
the surface of what could become possible in a world of open
source teaching collaboration.  Here we briefly consider
three areas: collaboration; assessment; and funding.

Open-source sharing enables collaboration; first, because
everyone has an equal stake in improving the shared resource;
and second because open-source makes it as easy for them
to improve the shared materials as it would be to modify
their own materials.  Hence, a logical next step for 
TeachPub.org would be to offer collaboration tools
analogous to what Github provides software developers:
to make it easy for you to make your own version
of a particular question, and to merge back in other
people's improvements to your material, easily and
selectively.  This "distributed
version control" (DVC) problem has been rigorously solved
in the software development domain, and DVC collaboration will be
integrated throughout TeachPub.org.

Systematic assessment of the efficacy (better vs. worse student
learning) of teaching materials or methods is only possible
when it can be deconvoluted from that of individual
instructors, i.e. when the same comparisons of different
materials are performed by multiple instructors.
For example, evidence of the superior performance of 
Peer Instruction methods only became convincing when it
was replicated at a variety of institutions.  In a word,
assessment requires reuse.  When you establish an open
market where all materials are available to all instructors,
you establish a strong foundation of reuse upon which
controlled measurements of efficacy could be 
automatically performed based on careful study designs.
Currently, developing such a study would be very challenging
because it would require recruiting multiple courses
to participate (e.g. run the same course once with method A,
once with method B, ideally multiple times), and possibly
even Human Subjects research approvals.  By contrast,
when many courses (and probably many independent, online
students) are studying the same concept on TeachPub.org,
randomized trials could be automatically performed on
a desired set of comparisons, e.g. to assess what question
most accurately measures understanding of that concept,
or what exercise(s) most effectively teach understanding
of that concept.  Performing such studies online could
provide both large sample sizes and rapid, real-time results.
In short, open-source teaching materials sharing could
act as a research platform for a greatly expanded
research field on the detailed measurement of teaching efficacy.
This in turn could feed back quickly and naturally to
direct the entire community of users to the empirical "best practices"
and most effective teaching materials.

The establishment of a fully open-source "market" of validated
teaching materials might also have implications for 
education funding.  Researchers "give away" (publish) their
innovations mainly because research funding agencies pay them
to do so.  Universities highly prize research innovation 
for the same reason.  Agencies or foundations that wish to
advance specific educational goals could establish competitive
funding mechanisms whose required end-product would be
(open-source) published teaching materials for those specific
goals.  Since such materials enable all possible forms of reuse,
an agency would have the assurance of gaining maximum impact
from their end-products.  By contrast, funding development of 
a MOOC would be like allowing a grantee to patent an 
innovation (to block others from using it)
without publishing the underlying research.

