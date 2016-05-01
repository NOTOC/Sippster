# Sippster
SIPP expansion. Does call validation and statistics in a nice xls, based on destination numbers input.
Provides output in handy excel file. Does analisis from header responses and from Q.850 reasons if available.
Excel information for each call:
Call status, Call ID, B number, Call start time, Call end time, Network call duration (in ms), User call duration, Call SIP sequence, Call headers

Input is a list of numbers in E.164 with your provider prefix. 
It requires your custom sipp call flow simulation and pcap if needed.

Whishlist: analyze call quality if B side answers.
