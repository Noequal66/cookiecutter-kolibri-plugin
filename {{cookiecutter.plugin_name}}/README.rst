
Kolibri External Plugin Template
=================================


How can I install external plugin in Kolibri?
-----------------------------------------------

Run the following commands in Kolibri to install this plugin:

``pip install -e <LOCAL_PATH_TO_THIS_PLUGIN_FOLDER>``


``kolibri plugin {{cookiecutter.plugin_name}} enable``

If the plugin includes any libraries in package.json, run ``npm install`` in Kolibri


What is Kolibri?
----------------

Kolibri is a Learning Management System / Learning App designed to run on low-power devices, targeting the needs of
learners and teachers in contexts with limited infrastructure. A user can install Kolibri and serve the app on a local
network, without an internet connection. Kolibri installations can be linked to one another, so that user data and
content can be shared. Users can create content for Kolibri and share it when there is network access to another
Kolibri installation or the internet.

At its core, Kolibri is about serving educational content. A typical user (called a Learner) will log in to Kolibri
to consume educational content (videos, documents, other multimedia) and test their understanding of the content by
completing exercises and quizzes, with immediate feedback. A user’s activity will be tracked to offer individualized
insight (like "next lesson" recommendations), and to allow user data to be synced across different installations --
thus a Kolibri learner can use his or her credentials on any linked Kolibri installation, for instance on different
devices at a school.

See https://learningequality.org/kolibri/ for more info.


How can I contribute?
---------------------

 * `Documentation <http://kolibri.readthedocs.org/en/latest/>`_ is available online, and in the ``docs/`` directory.
 * Mailing list: `Google groups <https://groups.google.com/a/learningequality.org/forum/#!forum/dev>`_.
 * IRC: #kolibri on Freenode
