dnsmasq
=======

dnsmasq for Asus &amp; Tomato

I try to keep this dnsmasq tracking http://www.thekelleys.org.uk/dnsmasq/doc.html as closely as possible
but with the various code used by ASUSWrt & Tomato - these extra tweaks (in essence changing how the
dhcp status file is updated & (in the case of Tomato) written out by a helper function) are wrapped in
'IFDEF' blocks, hopefully for ease of update.

Many tweaks that were originally tomato only have made it into the base release maintained by Simon, notably
the 'quiet-*' options.


This code should just copy in to pretty any much asuswrt-merlin or tomato source tree, compile & behave
properly.
