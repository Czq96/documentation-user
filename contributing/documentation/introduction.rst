:banner: banners/contributing.png

==================
Introduction guide
==================

**First of all, thank you for landing here and helping us improve the user documentation of Odoo.**

This introductory guide will help you acquire the tools and knowledge you need to write
documentation, whether you plan to make a minor content change or document an application from
scratch.

.. _contributing/rst-intro:

reStructuredText
================

Our documentation is written in **reStructuredText** (RST), a `lightweight markup language
<https://en.wikipedia.org/wiki/Lightweight_markup_language>`_ consisting of normal text augmented
with markup which allows including headings, images, notes, and so on. This might seem a bit
abstract but there is no need to worry, :abbr:`RST (reStructuredText)` is not hard to learn,
especially if you intend to make only small changes to the content.

If you need to learn about a specific markup, head over to :doc:`our cheat sheet for RST
<rst_cheat_sheet>` which contains all the information that you should ever need for the user
documentation of Odoo.

.. important::
   We kindly ask you to observe a set of :doc:`guidelines <guidelines>` as you write :abbr:`RST
   (reStructuredText)`. This ensures that you stay consistent with the rest of the documentation and
   facilitates the approval of your content changes as they are reviewed by a redactor at Odoo.

.. _contributing/getting-started:

Getting started
===============

As our documentation is maintained on GitHub, you will need a free GitHub account. Click `here
<https://github.com/join>`_ to create one.

Now, depending on whether you want to update existing content, or rather work on new content and
make file changes, you have two courses of action:

#. **For small changes** in ``.rst`` files only, i.e. addition/edition of paragraphs or typos, **we
   suggest that you use the GitHub interface**. This is the easiest and fasted way to submit your
   request for changes for the documentation and is suitable for non-technical people. Read
   :ref:`contributing/github-interface` to learn how to use this method.
#. **For more complex cases**, it is necessary to **use Git and work from a local copy of the
   documentation**. This method seems intimidating but only require basic knowledge of Git. See
   :ref:`contributing/canonical-git-workflow` for more information on this method.

.. _contributing/github-interface:

Contribute from the GitHub interface
====================================

#. Verify that you are browsing the documentation in the version that you intend to change. The
   version can be selected from the dropdown in the top menu.

   .. image:: media/version-selector.png

#. Head over to the page that you want to change and click on the **Edit on GitHub** button in the
   bottom of the left menu.

   .. image:: media/edit-on-github.png

#. If you do not have edit rights on the repository (`odoo/documentation-user
   <https://github.com/odoo/documentation-user>`_), you need to fork it by clicking on the
   appropriate button. Basically, you create a copy of the entire repository on your own account. If
   you do have the edit rights, skip this step.

   .. image:: media/fork-repository.png

#. Make appropriate changes while taking care of following the :doc:`guidelines <guidelines>`.

#. Click on the **Preview changes** button to review your contribution in a more human-readable
   format. Be aware that the preview is not able to handle all markups correctly. Notes, for
   instance, are not correctly rendered. The version of your content published to the website will
   be, however.

#. Go to the bottom of the page to commit (:dfn:`what packs your changes together and labels them
   with a commit message`) your changes.

   #. | In first text box, describe your changes. For instance, "Fix a typo" and "Document invoicing
        of sales orders" are two clear commit messages.
      | In the second text box, justify *why* you made these changes if you feel that it is not
        obvious.
   #. Select the option "Create a new branch for this commit and start a pull request." if you have
      the choice (if you have partial or full edit writes on the repository). If not, skip this
      step.
   #. Click on the green button. It is either labelled "Commit changes" or "Propose file change".

   .. image:: media/commit-changes.png

#. In the dropdown for the selection of the base branch (i.e., the version of the documentation that
   your changes concern), make sure to select the same version as in the first step of this guide.

   .. image:: media/select-base-branch.png

#. Click on "Create pull request" **twice** (a second button will appear) to submit your changes for
   review by a redactor at Odoo.

   .. image:: media/create-pull-request.png

#. You're done! If your changes are approved straight away, they will appear in the documentation
   the very next day. It may also be the case that the reviewer has a question or a remark, so make
   sure to check your notifications or your emails, depending on your account settings.

.. _contributing/canonical-git-workflow:

Contribute from the canonical Git workflow
==========================================

.. todo:: pngquant
