# DQM-L1TMonitorUpgrade

When this packaged is cloned locally, it should be placed in CMSSW_X_X_X/src/DQM/. The directory containing it should be renamed to L1TMonitor so that its paths match the rest of the CMMSSW package.

Files renamed:
 
	./interface/L1TCSCTF.h  -->  ./interface/L1TEMUTF.h
	./python/L1TCSCTF_cff.py  -->  ./python/L1TEMUTF_cff.py
	./python/L1TCSCTF_cfi.py  -->  ./python/L1TEMUTF_cfi.py
	./src/L1TCSCTF.cc -->  ./src/L1TEMUTF.cc

Lines renamed:
 
	./interface/L1TEMUTF.h, lines 66, 63, 58, 5, 2, 1
	./python/L1TEMUTF_cfi.py, lines 3 
	./python/L1TEMUTF_cff.py, lines 3
	./src/SealModule.cc, lines 12, 13
	./src/L1TEMUTF.cc, lines 2, 8, 25, 25, 38, 108, 108, 118, 121, 127, 652, 667, 672, 
	./python/L1TMonitor_cff.py, lines 55
	./doc/L1TMonitor.doc, lines 26, 63
