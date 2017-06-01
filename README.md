# richfaces-4.5

Fork of the [RichFaces 4.5.x sources](https://github.com/richfaces/richfaces) for patches needed by Nuxeo.

You can check the original [README](https://github.com/nuxeo/richfaces-4.5/blob/master/README.adoc) in the master branch.

# Purpose

We need to patch RichFaces 4.5.0.Alpha3 on which Nuxeo 7.10 is relying.

The patches are done in the [4.5.0.Alpha3-NX](https://github.com/nuxeo/richfaces-4.5/tree/4.5.0.Alpha3-NX) branch (default) that has been checked out from the [4.5.0.Alpha3](https://github.com/nuxeo/richfaces-4.5/tree/4.5.0.Alpha3) tag.

Build Status for this branch: [![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=Vendor/richfaces-4.5.0.Alpha3-NX)](https://qa.nuxeo.org/jenkins/job/Vendor/job/richfaces-4.5.0.Alpha3-NX/)

Note that versions of Nuxeo >= 8.10 are relying on RichFaces 4.5.12.Final which doesn't need any patch for now.

# How to Build

    mvn clean install
