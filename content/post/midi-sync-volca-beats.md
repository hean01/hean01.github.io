+++
date = "2015-12-03"
title = "Midi sync Volca beats with Analog four"
tags = ["music", "volca", "midi" ]
categories = ["Electronc Music"]
+++

I just recently got my Volca Beats analog drum machine and wanted to
sync it up with my Analog Four. To enable Volca Beats to sync with
external device using midi you need to make sure that clock source is
configured to `auto`.

While holding down `func` key and power on the volca device, you will
enter configuration mode of the Volca Beats. Pressing `play` button
will cancel any changes, `record` will save the changes and reboot
your device. The configuration of clock source is done with step
button 6, if this led is lit, clock source is configured to `auto`
which is needed to sync with external midi clock.

You also need to configure the Analog Four to send midi clock and
transport midi messages. Access the global menu using the combination
of `func + C2` keys. Navigate to menu entry `MIDI SYNC` and hit `yes`
button, then set the send midi clock and transport. Hit _no_ button to
get back to global menu and enter `MIDI PORT CONFIG` menu. Make sure
that `OUT PORT FUNC` is configured as `MIDI`.
