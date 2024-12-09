# THIS IS MY PERSONAL MIRYOKU LAYOUT FOR CHOCOFI AND BADWINGS KEYBOARDS

If you want to change the layout to you liking, change the 'qwertz' layers inside ./users/manna-harbour_miryoku/miryoku_babel/miryoku_layer_alternatives.h

To build the firmware, run:

- chocofi:
    qmk flash -kb crkbd -km manna-harbour_miryoku -e MIRYOKU_ALPHAS=QWERTZ -e MIRYOKU_NAV=VI
- badwings
    qmk compile -kb hazel/bad_wings -km manna-harbour_miryoku -e MIRYOKU_ALPHAS=QWERTZ -e MIRYOKU_NAV=VI
