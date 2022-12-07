
# Reliability Requirements 

2.0 The E-Commerce Store shall be scalable enough to support 1,000,000 visits at the same time while maintaining throughput of 5 seconds.

2.1 The E-Commerce Store shall perform without failure in 95 percent of use cases during a month.
        
   &emsp;&emsp;2.1.1 The E-Commerce system shall be available to Pakistani Users 99.9 percent of time every month during the business hours according to UTC+ 05:00

2.2 The E-Commerce store shall be recoverable in a mean time of less than 10 minutes in case of a failure.

2.3 The E-Commerce store shall follow the guidelines of  ISO/IEC 25000.

2.4 The E-Commerce store shall have to be compatible with Amazon CloudFront.

# Secrity Requirements
3.0 The E-Commerce store shall have to be compliant with GDRP.

3.1 The E-Commerce store shall available and behave reliably even under DOS attacks within 5 minutues of attack.

3.3 The E-Commerce store shall protect the 99.99 percent of customer account information.

   &emsp;&emsp;3.3.1 The E-Commerce store shall Encrypt all Personally Identifiable Information (PII) at rest with usage of Argon2 Encryption algorithm.

   &emsp;&emsp;3.3.2 The E-Commerce system allow the users to use Two-Factor Authentication.

3.4 The E-Commerce Store shall backup the necessary data after 1 week regularly.

3.5 The E-Commerce Store shall allow 5 failed login attempt to a valid user.
