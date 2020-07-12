### bank-cheque-reader-using-text-recognition
The project aims to read bank cheques (specifically the handwritten Payee Account Number and Amount) which can stored by banks for further transactional use.

For recognition of a series of numerals, contour tracing and merging algorithms are used to read a single or two digits as a single contour and recognize them.

Length estimator is trained using single digit images from NIST SD19 two digit string images are used from the Synthetic Digit Strings Dataset. Then 10 class and 100 class classifiers are trained from these dataset respectively to achieve a highly accurate performing system.

The cheque_reader then uses all these trained models to read the data on any cheque.

