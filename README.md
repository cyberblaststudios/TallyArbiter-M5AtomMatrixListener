# TallyArbiter-M5AtomMatrixListener
This is a Tally Viewer using a M5 Atom Matrix as a TallyArbiter Client.
This is my attempt at 'mushing' arduino code.
* Buy them here:
https://m5stack.com/collections/m5-atom/products/atom-matrix-esp32-development-kit

# Videos

* What this does when used with TallyArbiter - https://youtu.be/hNhU22OkXek
* Demo of the M5Atom Matrix code in this git - https://youtu.be/Mc_PCxg6qdc
* Demo running on 10 M5Atom Matrix units via a cloud server - https://youtu.be/TiqjmXdzPic
* RAW Step-By-Step Install - With warts and all on a fresh windows installation - https://youtu.be/soj1Cxv3mLY

# Current Updates
* Tidyed up things a little bit
* Changed the way the LED's are written to now using the M5 library
* Added Blank and 1 thru 16 camera numbers by pushing the screen (M5 Action button)
* Fixed bugs

Note if deploying yourself, one of the librarys has an error where you have to manually comment out hexdump by changing it to //hexdump

# Planned Updates
Next Update will have Internal Motion Unit functionality to automatically rotate the screen.

# Thanks
Thanks to mg-1999 for the code base, and huge thanks to josephdadams for his amazing work on TallyArbiter, and the origional M5StickC implementation.
https://github.com/josephdadams/TallyArbiter
