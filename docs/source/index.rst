Welcome to AssistYou's telephone platform documentation!
=========================================================

AssistYou creates digital assistants to support your customer service. Our digital hosts can identify callers,
help them with some of their questions, and route them to the right deparment. When routing to a customer service representative, AssistYou can provide information about the call 
that just took place, via a CTI integration.

This documentation is meant to inform our customers about what kind of set ups we support, and how to connect with us over SIP.
AssistYou always works with two separate environments:

*Acceptance* & *Production*. We therefore require a trunk to be set up for both environments.

Our acceptance environment is meant for testing our digital assistant, for both ourselves and our customers. It is therefore required that this environment is *kept running after go-live*, as we will always first deploy to this environment, and test there, before moving to production.

We require a *public phone number* for each environment, that then calls AssistYou via the right SIP trunk.  
If your phone numbers are limited by opening times, AssistYou requires a separate 24/7 phone number, so both environments can be reached at all times.

Check out our :doc:`recommended_sip_setup` to see how we connect to most of our customers. For a complete overview, please refer to :doc:`sip_connection_options`

.. note::

   This project is under active development. For any questions, please contact development@assistyou.ai


Contents
--------

.. toctree::

   recommended_sip_setup
   sip_connection_options
   genesys_cloud_setup
