Information about the Air Routes graph.  

Timestamp: Sat, 31 Jul 2021 13:41:40 -0500

This file contains the following sections
  1. Introduction
  2. Some statistics about the graph


1. INTRODUCTION 

The graph provides a model of the world commercial airline route network. It
remains a  work in progress but I have tried to curate the data carefully.
However,I do not doubt there are errors and omissions that remain. This is
intended  as a learning tool and not for actual travel planning purposes!  If
you spot any errors such as missing routes or routes that are no longer served,
please do let me know.

I have tried to verify that a connection between airports is only given if at
least one commercial airline currently operates scheduled service between them.
Given the dynamic nature of the airline industry where routes are added and
removed on a weekly basis any graph such as this one is, invariably, out of
date the day it is published. That said I have tried to keep the graph as up to
date as I can.  

This graph only models airports and routes it does not attempt to model airlines
or route frequency. For example, the graph can tell you that there is a route
between LHR and JFK that at least one airline operates but not which airlines
fly that route nor how many times a day the route is operated. That is an
exercise for another day and for a bigger graph! The graph also does not
currently contain any aircraft information.  For the most part I have only
included scheduled flights flown by commercial airlines. I have included a few
unusual routes such as the flights from RAF Brize Norton to RAF Ascension Island
continuing on to Mount Pleasant in the Falkland Islands as I believe this
represents a significant route and is a sort of pseudo-scheduled flight. I do
not include routes flown only by freight carriers like FedEx and UPS. I also
have only mostly included airports with at least one route. There are a few
exceptions such as St. Helena which is a new airport with service pending, but
delayed, due to issues with wind shear. Where an airport has no flights but
remains in the graph it is probably because it was served by commercial airlines
at some point. It is also useful for people learning to search graphs to be able
to query for orphan nodes so for that reason as well I have left them in the
graph.

All of this said, I believe, as a learning tool there is plenty in the graph to
facilitate writing some interesting queries and if you are so inclined for
producing nice visuals. I hope people have as much fun playing with the graph
as I have had putting it together.

Please do let me know of any mistakes you find or about airports and/or routes
that are currently missing. I believe I have most of the airports from around
the World that offer scheduled airline service included in the graph at this
point. The one exception is about ten regional airports in China that I
still need to add 
   
If you require more detailed information about the schema of the graph  and
it's overall demographic please see the comments at the top of the
air-routes.graphml file.
 

2. SOME STATISTICS ABOUT THE GRAPH

Air Routes Graph (v0.86, 2021-Jul 31st) contains:
  3,502 airports
  50,656 routes
  237 countries (and dependent areas)
  7 continents
  3,747 total nodes
  57,660 total edges

Additional observations:
  Longest route is between SIN and EWR (9,523 miles)
  Shortest route is between WRY and PPW (2 miles)
  Average route distance is 1,207.836 miles.
  Longest runway is 18,045ft (BPX)
  Shortest runway is 1,300ft (SAB)
  Average number of runways is 1.4209
  Furthest North is LYR (latitude: 78.2461013793945)
  Furthest South is USH (latitude: -54.8433)
  Furthest East is SVU (longitude: 179.341003418)
  Furthest West is TVU (longitude: -179.876998901)
  Closest to the Equator is MDK (latitude: 0.0226000007242)
  Closest to the Greenwich meridian is LDE (longitude: -0.006438999902457)
  Highest elevation is DCY (14,472 feet)
  Lowest elevation is GUW (-72 feet)
  Maximum airport node degree (routes in and out) is 614 (FRA,IST)
  Country with the most airports: United States (586)
  Continent with the most airports: North America (989)
  Average degree (airport nodes) is 28.930
  Average degree (all nodes) is 28.915
 
 
Here are the top 50 airports with the most routes
 
    POS  ID   CODE  TOTAL     DETAILS

     1	 161   IST  (614)  out:307 in:307
     2	  52   FRA  (614)  out:307 in:307
     3	  51   CDG  (589)  out:294 in:295
     4	  70   AMS  (568)  out:283 in:285
     5	  80   MUC  (543)  out:271 in:272
     6	  18   ORD  (527)  out:264 in:263
     7	   8   DFW  (502)  out:251 in:251
     8	  64   PEK  (497)  out:248 in:249
     9	  58   DXB  (494)  out:247 in:247
    10	   1   ATL  (484)  out:242 in:242
    11	  50   LGW  (466)  out:233 in:233
    12	 102   DME  (465)  out:232 in:233
    13	  49   LHR  (442)  out:221 in:221
    14	  31   DEN  (432)  out:216 in:216
    15	  84   MAN  (431)  out:216 in:215
    16	  13   LAX  (426)  out:213 in:213
    17	  94   STN  (425)  out:212 in:213
    18	  67   PVG  (424)  out:212 in:212
    19	  74   MAD  (414)  out:207 in:207
    20	  75   VIE  (412)  out:206 in:206
    21	  73   BCN  (408)  out:204 in:204
    22	  68   FCO  (404)  out:202 in:202
    23	  12   JFK  (401)  out:201 in:200
    24	 198   DUS  (398)  out:199 in:199
    25	  11   IAH  (398)  out:199 in:199
    26	  35   EWR  (394)  out:197 in:197
    27	 177   CPH  (390)  out:195 in:195
    28	  79   BRU  (390)  out:195 in:195
    29	  47   YYZ  (390)  out:195 in:195
    30	  16   MIA  (390)  out:195 in:195
    31	 106   DOH  (372)  out:186 in:186
    32	  60   DUB  (372)  out:186 in:186
    33	 178   CLT  (368)  out:184 in:184
    34	 103   SVO  (364)  out:182 in:182
    35	  76   ZRH  (360)  out:180 in:180
    36	  61   HKG  (348)  out:174 in:174
    37	 250   CAN  (347)  out:175 in:172
    38	 122   ICN  (346)  out:173 in:173
    39	  93   ARN  (338)  out:169 in:169
    40	  56   SIN  (335)  out:168 in:167
    41	  30   LAS  (322)  out:161 in:161
    42	 346   LED  (320)  out:160 in:160
    43	  15   MCO  (320)  out:160 in:160
    44	   9   FLL  (314)  out:157 in:157
    45	  23   SFO  (312)  out:156 in:156
    46	  17   MSP  (312)  out:156 in:156
    47	  10   IAD  (310)  out:155 in:155
    48	 200   TXL  (309)  out:154 in:155
    49	 230   PMI  (306)  out:153 in:153
    50	 110   ATH  (306)  out:154 in:152
 
 
Here are the longest routes currently in the graph
 
SIN->EWR 9,523
EWR->SIN 9,523
DOH->AKL 9,025
AKL->DOH 9,025
PER->LHR 9,009
LHR->PER 9,009
PTY->PEK 8,884
PEK->PTY 8,884
DXB->AKL 8,818
AKL->DXB 8,818
SIN->LAX 8,756
LAX->SIN 8,756
MEX->CAN 8,754
CAN->MEX 8,754
SYD->IAH 8,591
IAH->SYD 8,591
SYD->DFW 8,574
DFW->SYD 8,574
MNL->JFK 8,504
JFK->MNL 8,504
JNB->ATL 8,434
ATL->JNB 8,434
SIN->SFO 8,433
SFO->SIN 8,433
LAX->AUH 8,372
AUH->LAX 8,372
LAX->DXB 8,321
DXB->LAX 8,321
LAX->JED 8,314
JED->LAX 8,314
LAX->DOH 8,287
DOH->LAX 8,287
RUH->LAX 8,246
LAX->RUH 8,246
TLV->SCL 8,208
SCL->TLV 8,208
YVR->MEL 8,197
MEL->YVR 8,197
ORD->AKL 8,186
AKL->ORD 8,186
IAH->DXB 8,150
DXB->IAH 8,150
SFO->AUH 8,139
AUH->SFO 8,139
IAD->HKG 8,135
HKG->IAD 8,135
HKG->DFW 8,105
DFW->HKG 8,105
SFO->DXB 8,085
DXB->SFO 8,085
SIN->SEA 8,059
SEA->SIN 8,059
JFK->HKG 8,054
HKG->JFK 8,054
DFW->AUH 8,053
AUH->DFW 8,053
HKG->EWR 8,047
EWR->HKG 8,047
IAH->DOH 8,030
DOH->IAH 8,030
DXB->DFW 8,022
DFW->DXB 8,022
