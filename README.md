# yet-another-internet-radio

Another semi-decent internet radio, based on VS1053 decoder and ESP8266 MCU, made from scratch solely for my midnight engineering sessions.

It plays anything that VS1053 may decode.

## Features:
- ESP8266 MCU
- VS1053 decoder
- 23LC1024 1 Mbit SRAM
- 2x3W PAM8034 amplifier
- 20 x 4 alphanumeric LCD
- 3 buttons

Station list is stored into a remote hosted JSON file: [irconfig.dat](http://pisicaverde.ro/irconfig.dat)
(.dat extension used since cPanel is weirdly caching .json files)

Where it all started: [Arduino WebPlayer by Vassilis Serasidis](https://www.serasidis.gr/circuits/Arduino_WebRadio_player/Arduino_WebRadio_player.htm)

![Schematics](https://lh3.googleusercontent.com/N3HAeYrSaEksZR7SAeC6bDKn3Zf736JcLFpJFX6m2_E5M2fhwSd6ob9YXm2dyn2qbhbEk39nLgL0Mvkkt5uZxvg_AR-2KNuTy6MeDfw3EU7If4DtibhLjMVV3SqZWCwt6JYe71qrP_KBDPVcBpP2rXTrXbCv-EroglRehAdI-0lWvGd7bT0UhcEYckQvQHHceN9txJOYZyKJrnPc9_9NUyHTcKbtZy3lVfEgtvv-6SuXpjy6Rxeh2Co4V333BUSAjwYJ9blcU1dFGI55C9QSsqvbakejQgssRWB6J0MOLdp1oGD8sXnVeORWIBDjfPRc9lQFc1WHz5tpq01dXfUR8ZwUUIH7xRjNVX53RNR8GW-d1dttV-qaaORuJH-vpT_G4RiBZzCq2WoQRtKoe2EcPMQpbcjJLHbnfizS96ViashzFZQgKnjh_updBHZ6WdNo4yvb6DNE9KH7Rfx2Nu1glKxyg26Z2OniJJfqbZbGSRbobMzX7zRZD4vVMFLVpaJAejQNc0P2krOb1jypTHbRwyFhh5E0S4UL2KxGJ5kTkvFT9jd0C3QUMBC4DopTRMuR20cu9pSzZ4ADvh8jqxdJaewrtuycekCb-6lCSirWvlzOXoMqMyyQeWiiIMq8O8ZP=w1031-h585-no)


Photos with some unfinished works:
![Photos](https://lh3.googleusercontent.com/1XV7Ls_McwR1Gsm5v5TV9fn4OgXxtyYwKhF4N0pbtUxZkLK-AJ_3BbRByZnaPsFHGnRmrSB4-NM1-y-37bpOmzYlDcUIYFG7DqUqtL0_aSErIsEDM2pZiXgCsvH87-BkYxhr2iyYx-zTD8TXKMG58-4CCrYCn_lhfvrpX_nn2MYjbkJNtugyFv1fWExW2Bc6kh7nYdf5U8Fsx8CgqCSo2tDRnU97J3-5wp0dA2dPwUVcuIfrcToctCsdJF6wKuKJT5sje99FZ4KVaTyUMkoYHvGARLS6fgmmm_1_-t4C1OFmWFnlYjiODMpxABFgRTQQP_K6War4XQ0XgWAAMSD2R5566XFzVjT8VCEhwcv2hvu656tV3AqROD9XF2EVWQmFERW8PdQ_JiIjAfo4UP52o01zxlj-B2W53liT_x_p-dtmv_Slv4s4kLjh0ZlWisIg1fRsYOcFMaMVZzC6V024FsJ9u4Ww9TbMUWU1pHQmUdj1dpWaxGULvnSKboC-iMU_DtGAkja28lw0pITdC6X-qJmEoagsvLOh0AU2MbtlxJYBaAKaLo73nrycmyqBV9Wee4x7HW1bUGSBvzzU9vpOPc08n7-g-ZBwN0pAT_I6vdwHhFvE_Lobo9MoU5z2d7F_GdAcbDQUDBn6dabq2U0O-rFYV-iZ16nE77qZSeS6WKdgsT75wy-mJ3CNew=s1080-no)
