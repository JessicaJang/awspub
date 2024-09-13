How to install awspub
=====================

Setup profile configuration
---------------------------

Before using this tool, you need to setup the AWS configuration and credential files. Follow
`CLI configuration documentation`_ to create these two files.

Example config file:

.. code-block::

    $ cat ~/.aws/config
    [default]
    region = us-east-1

Example credential file:

.. code-block::

   $ cat ~/.aws/credentials
   [default]
   aws_secret_access_key = <YOUR SECRET ACCESS KEY>
   aws_access_key_id = <YOUR ACCESS KEY ID>

Install awspub using snap
-------------------------

`awspub` is available in the `Snapstore`_, and it can be installed using:

.. code-block::

    snap install awspub

This will install the latest version in your machine. We would highly recommend you install the latest version, but
refer to this `Snapcraft channel doc`_ for installing a different version or from a specific channel.

CLI usage
---------

The command line interface called ``awspub`` accepts the standard AWS environment variables such as `AWS_PROFILE`.

.. _`CLI configuration documentation`: https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html#cli-configure-files-using-profiles
.. _`Snapstore`: https://snapcraft.io/awspub
.. _`snapcraft channel doc`: https://snapcraft.io/docs/channels
