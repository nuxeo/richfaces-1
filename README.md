# richfaces-4.5

Fork of the [RichFaces 4.5.x sources](https://github.com/richfaces/richfaces) for patches needed by Nuxeo.

You can check the original [README](https://github.com/nuxeo/richfaces-4.5/blob/master/README.adoc) in the master branch.

# Purpose

We need to patch RichFaces 4.5.12.Final on which Nuxeo 8.10 and higher is relying.

The patches are done in the [4.5.12.Final-NX](https://github.com/nuxeo/richfaces-4.5/tree/4.5.12.Final-NX) branch (default) that has been checked out from the [4.5.12.Final](https://github.com/nuxeo/richfaces-4.5/tree/4.5.12.Final) tag.

Build Status for this branch: [![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=Vendor/richfaces-4.5.12.Final-NX)](https://qa.nuxeo.org/jenkins/job/Vendor/job/richfaces-4.5.12.Final-NX/)

# How to Build

    mvn clean install
