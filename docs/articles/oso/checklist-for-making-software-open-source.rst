:orphan:

Checklist for making software open source
=========================================

.. tagslist:: howto

When making software open source there are some steps that need to be completed.
The purpose of these steps is to ensure that the code has a sound license, the
source code repository is understandable and that there are clear descriptions
on how to contribute. Following is a listing of these steps:

#. Pick an open source license [#owning_copyright_required]_.
#. Make sure that the license of all dependencies of the software fit the
   desired license.
#. Make sure that the following files are present in the root of the source code
   repository:
    * LICENSE: Containing the desired license for the code
    * README.md: Containing information on where to find the documentation and
      simple getting started info.
    * CONTRIBUTING.md: Containing information on how to contribute to the
      project and what rules there are.
#. Go through file headers of all the source code and make sure that there is a
   copyright notice, a reference to the LICENSE file and a SPDX tag
   [#owning_copyright_required]_.
#. Send a request to make the software open source to the Open Source Office
   (OSO). The request should contain an accessible link to the source code
   repository, a statement of what the desired license is as well as a list
   of business use cases the software needs to fulfill.
#. The OSO makes sure that the desired license fits the business use cases.
#. The OSO scans the code to make sure that it is compliant with the desired
   license.
#. The OSO registers that the software has been open sourced using the desired
   license in the OSO decision log.
#. The code is ready to be pushed to a public repository.

.. [#owning_copyright_required] In order to change the license of a peice of
   source code, owning the copyright of said source code is required.
