## TRANSCRIPT

0:00     
hello this is Dr Bradley Alisa and I'm     
0:02     
going to be giving an update on the     
0:04     
activities for Diva worm over the year     
0:08     
20124 so that's from November of 2023 to     
0:11     
November of     
0:13     
2024 so this is the 10th year     
0:15     
anniversary of D.A we've been doing     
0:17     
computational developmental biology for     
0:19     
a decade so you can see in the     
0:22     
background image we have this timeline     
0:24     
with different types of projects on it     
0:26     
and I was pleasantly surprised going     
0:28     
through all the things we've done over     
0:30     
the past 10 years and we've done such a     
0:32     
diversity of things and how those     
0:34     
approaches have been Incorporated in our     
0:36     
talks and papers and meeting activities     
0:40     
and so there's a link to our YouTube     
0:42     
channel where we have I've put an hour     
0:45     
and a half long video on 10 years of     
0:48     
computational Developmental     
0:51     
biology so evil worm started in April of     
0:54     
2014 so it actually was initiated by     
1:00     
a GitHub issue and that was on the     
1:02     
openworm foundation's organizational     
1:06     
GitHub issue number 179 so you can see     
1:09     
that Steven     
1:10     
Larson put this issue up he basically     
1:14     
put some goals on here uh basically find     
1:17     
a data source that allows us     
1:20     
to find uh you know the lineage tree for     
1:24     
seans which is well known and     
1:26     
published and bringing that into a     
1:28     
computational environment     
1:31     
so we did this with our first paper we     
1:32     
worked on this uh we produced an rdf     
1:35     
representation of this and it was a good     
1:38     
starting point um but we didn't directly     
1:40     
solve this problem because we didn't     
1:42     
incorporate it into Pi openen one     
1:45     
however we did do a lot of other things     
1:47     
after that and so our first meeting was     
1:50     
in April 11th of 2014 the attendees were     
1:54     
Steven lison myself and Dr Richard     
1:56     
Gordon and we met in Google Hangouts     
1:59     
which doesn't exist anymore but we     
2:00     
talked about how to sort of get started     
2:03     
and we started that first paper which is     
2:05     
on the archive and then we continued on     
2:08     
with many other projects over the years     
2:10     
so every year since 2017 we've been     
2:13     
involved with googal Summer of code or     
2:15     
gso and this year we sponsored two     
2:18     
students we sponsored mul Aurora who did     
2:21     
this project called hyper devor graph     
2:24     
which is creating hyper grass for the     
2:25     
seans embryo from the lineage tree data     
2:29     
and Pocky Balia who did a project on     
2:33     
growing uh developmental graph neural     
2:36     
networks with neural developmental     
2:39     
programs and so both students     
2:41     
contributed to the D graph repository of     
2:43     
dvo learn at this GitHub address and     
2:47     
they contributed both of their projects     
2:49     
as directories in this repository so if     
2:52     
you're interested in contributing in an     
2:54     
open source fashion please check this     
2:56     
repository     
2:58     
out so the first part of picky's project     
3:01     
was the application of the Kepler mapper     
3:03     
or k mapper algorithm to the C Elan     
3:06     
lineage tree and so this is on the left     
3:09     
um sort of a visualization of the     
3:11     
lineage Tree in terms of topological     
3:14     
data analysis which allows us to look at     
3:16     
sort of the shape of the data so the     
3:19     
data has a certain shape want to     
3:20     
characterize those shapes and visualize     
3:23     
things so we can get a better handle on     
3:25     
the data um this was visualized in a     
3:28     
Mathematica applet specifically for this     
3:31     
purpose and it looks kind of like a umap     
3:34     
although it's not it has a bit more     
3:36     
information in it and different type of     
3:39     
information so uh this is a fork of     
3:42     
Luca's TDA mapper in Python so that repo     
3:46     
was forked by Pocky and we were working     
3:48     
from that     
3:49     
fork uh topological data analysis was     
3:53     
conducted on the celan lineat Tre data     
3:56     
it allowed us to preserve the cell     
3:59     
nomencl the line of descent and     
4:01     
positional data and to characterize how     
4:04     
those sort of fall in terms of shape and     
4:07     
then this contributes to a     
4:09     
characterization of the underlying shape     
4:10     
of the data so one step in building     
4:14     
graphs is to characterize kind of the     
4:17     
connectivity and the sets of     
4:19     
relationships between the nodes which     
4:21     
represent the cells of certain do     
4:23     
clature a certain line of descent in     
4:25     
that lineage tree and a certain position     
4:28     
in the embryo the other thing that uh     
4:31     
Pocky did was neural developmental     
4:33     
programs so this uh was forked from Eli     
4:37     
Elias Naro GitHub project which is this     
4:40     
NDP project and this is not wasn't made     
4:45     
specifically for what we were trying to     
4:46     
do but we tried to to work around it the     
4:48     
best we could and modify the neural     
4:50     
developmental     
4:52     
programs basically it allows you to grow     
4:54     
a network from a single cell to multiple     
4:57     
cells and they use this for neural net n     
4:59     
works but we can use this for our own uh     
5:04     
uh embryo networks and specifically     
5:06     
tying it to the lineage tree and the     
5:09     
spatial position of cells so this model     
5:12     
was trained with see Elan embryo data     
5:14     
for the purposes of gck the network     
5:17     
grows as a cell divides you can see on     
5:19     
the left you have this visualization of     
5:22     
cells expanding and then the connections     
5:25     
between them and the way that these     
5:27     
graphs are plotted out is that these are     
5:30     
kind of forc directed graph projections     
5:32     
so they're not always going to match     
5:34     
what it looks like in the     
5:36     
embryo and any case we have different     
5:39     
connectivity Criterion and click     
5:41     
membership so click membership is where     
5:43     
you have a bunch of nodes that are     
5:45     
tightly connected together fully     
5:48     
connected and usually those uh match up     
5:51     
to the lineage tree so this means that     
5:55     
these cells have a common set of     
5:56     
descendants and have a common sort of     
5:59     
our common part of the embryo so there's     
6:01     
some spatial distance between them but     
6:03     
they're sort of cluster in the same part     
6:05     
of the embryo and so Po's project was     
6:08     
this graph neural network neural     
6:10     
developmental program hybrid model and     
6:14     
we're you know I think we made a lot of     
6:16     
progress on it this summer we're trying     
6:18     
to work on it for next summer and so if     
6:20     
you're interested in participating in     
6:22     
gck for next summer let us     
6:25     
know uh we also have three lectures     
6:28     
during 2024     
6:30     
the first being this mathematics a Divo     
6:32     
worm presentation which goes through all     
6:34     
the mathematical models and     
6:36     
developmental computational     
6:38     
representations we use in DVA work so     
6:40     
this is where we have different models     
6:43     
for connectomes for embryos for modeling     
6:45     
behavior and all these things and and if     
6:48     
it's exposition of all that work so this     
6:51     
was presented at the society for     
6:53     
mathematical biology cell and     
6:54     
developmental biology Festival this was     
6:57     
held virtually and you can find the uh     
7:00     
recording of this talk here um on our     
7:03     
YouTube channel uh so then we also had     
7:06     
uh two other talks it was basically an     
7:09     
extension of the work we've been doing     
7:10     
in our meetings the first is called     
7:13     
dimensions of morphogenesis which are     
7:15     
different you know models from     
7:17     
morphogenesis covering onedimensional     
7:19     
two-dimensional and higher dimensional     
7:21     
models of     
7:22     
morphogenesis that can be found on our     
7:24     
YouTube channel as well and then a     
7:27     
10,000 meter view of Deva learn so DVA     
7:30     
learn is this software uh package that     
7:33     
we've been building over the last five     
7:35     
or so years putting in all sorts of     
7:37     
things pre-train models graph neural     
7:40     
networks uh different types of uh models     
7:44     
like uh segment anything and so forth so     
7:48     
this is you know kind of coming together     
7:50     
we've had a lot of people work on this     
7:52     
and that can be found on our YouTube     
7:53     
channel as well we've also done a number     
7:56     
of papers this year the first paper was     
7:59     
this molecular basis of differentiation     
8:01     
wave activity     
8:02     
embryogenesis this was myself Sosh     
8:06     
bastani a Natalie Gordon Richard Gordon     
8:09     
and susin Crawford young and this was     
8:11     
published in biosystems a couple months     
8:14     
ago and the idea behind this paper is     
8:17     
we're trying to identify signatures of     
8:19     
these things called differentiation     
8:21     
waves so differentiation waves it's the     
8:23     
sort of uh reinterpretation of all the     
8:26     
different types of waves that are found     
8:29     
Andel     
8:30     
we have all sorts of waves such as     
8:31     
calcium waves or signaling waves or     
8:35     
other types of waves that go through     
8:37     
electrical activity that go through     
8:39     
populations of cells so there are these     
8:41     
different waves that happen in tissue     
8:43     
and cell populations that drive changes     
8:46     
in cell type and differentiation so you     
8:49     
have some array of cells in     
8:53     
embryogenesis there's a wave that goes     
8:55     
through them and then there's a     
8:57     
differentiation mechanism gets triggered     
8:59     
in these cells and they differentiate     
9:01     
behind the wave so this is uh you know     
9:04     
just a way to reinterpret the literature     
9:06     
but also a way to describe you know what     
9:09     
happens when you have Collective     
9:10     
differentiation when you have     
9:12     
differentiation over a whole bunch of     
9:14     
cells and you end up with this sort of     
9:17     
tissue     
9:19     
morphogenesis and so the other aspect of     
9:22     
this paper is we used form model     
9:23     
organisms we use secondary uh genetic     
9:27     
and proteomic data to look at four     
9:30     
different um systems seans of course     
9:34     
that's where the bulk of the work was     
9:35     
conducted dropil     
9:38     
melanogaster Mouse and yeast orac cabier     
9:42     
so we did we did we got protein     
9:45     
proteomic data for all of them and     
9:47     
genomic data for sea     
9:50     
elegant and we had these models that we     
9:52     
used to understand the interactions     
9:55     
between genes and seans and how they     
9:58     
relate to protein expression and so we     
10:01     
could then map that to sort of a model     
10:03     
of how these things might set up     
10:06     
differentiation waves and act in     
10:08     
development so that required us to do     
10:10     
some literature search for candidate     
10:12     
genes and candidate proteins and to get     
10:14     
some secondary data sets on gene     
10:16     
expression and early and late     
10:18     
embryogenesis so once we had the gene     
10:20     
expression data we could build these     
10:22     
interaction models which are not genetic     
10:25     
regulatory networks but they're you know     
10:28     
fully connected and sequential models     
10:31     
that allow us to sort of understand the     
10:34     
relationship between candidate genes and     
10:37     
proteins and their contribution to     
10:39     
things in     
10:41     
development and so this is another     
10:43     
example of some of the work we did     
10:45     
here we had a bunch of genes and looking     
10:49     
at their variation of their expression     
10:51     
and development and their expression     
10:54     
level and building a surface that     
10:56     
describes how those genes are related to     
10:59     
proteins what proteins are most active     
11:01     
in development which proteins are least     
11:04     
active in development and what that     
11:07     
surface looks like so you can see that     
11:09     
there are some genes that are very     
11:10     
interesting from this plot and some that     
11:13     
are less interesting but maybe also     
11:15     
important in some of these uh Cascades     
11:18     
involving the propagation of these waves     
11:21     
and then what happens after the cells     
11:23     
get that signal and different start to     
11:26     
differentiate so we have gene expression     
11:29     
space on the left and on the right we     
11:31     
have an example from dropa the imaginal     
11:35     
dis in dropo which will become the     
11:36     
compound eye so this is a high     
11:38     
resolution drawing of drop imaginal disc     
11:42     
and you can see that there are these     
11:43     
highlight ordered cell populations     
11:46     
called omidia on the right these are     
11:48     
multiple cell types that are ordered in     
11:50     
a certain way spatially and     
11:54     
functionally in the middle you have this     
11:56     
blurry area this R dense area called the     
11:58     
furrow and that's our wave that's going     
12:00     
through from right to left actually I     
12:03     
think the image is inverted so it's left     
12:04     
to right but the furrow is moving     
12:07     
through this tissue on the back side you     
12:10     
have the idia the differentiated tissue     
12:13     
on the right side you have     
12:14     
undifferentiated cells that are sort of     
12:17     
random at low density and so the idea is     
12:21     
wave sweeps through these Cascades     
12:24     
become triggered it contributes to     
12:28     
differentiation and you get this tissue     
12:30     
that emerges so this is an interesting     
12:33     
model the DAT is from cigan the example     
12:37     
is from dropa but seeing that there     
12:40     
these mechanisms that are parallel are     
12:42     
helpful in sort of understanding what     
12:45     
proteins and genes are involved in     
12:47     
this the other paper we worked on in     
12:50     
2024 is this section it's on     
12:53     
hypergraphs in anatomical hypergraphs in     
12:57     
development so this is called hyper     
12:59     
graphs demonstrate anastomoses during     
13:01     
Divergent integration we would like to     
13:03     
add to it I'll show you some of the work     
13:05     
that might add on to this might improve     
13:07     
this uh work but so basically we define     
13:10     
hyper graphs as nodes and edges that are     
13:14     
contained within hyper nodes and Hyper     
13:16     
edges so you can see that on the lower     
13:18     
right you have these hyper nodes and     
13:20     
inside each of these hyper nodes you     
13:22     
have a bunch of cells or nodes that are     
13:25     
connected through edges those edges then     
13:27     
can be bundled into hyper edges     
13:30     
and they can show sort of selective     
13:32     
connectivity between structures as we     
13:34     
saw before we have tissue types that     
13:36     
have a bunch of cells in them those     
13:38     
tissue types can be hyper nodes hyper     
13:41     
edges can be connections between     
13:43     
different tissue types whereas the nodes     
13:45     
and edges can be connections between     
13:46     
different cells and they're connect you     
13:49     
know they're maybe they're signaling     
13:51     
relationships so this can reveal     
13:54     
subgraphs of selective     
13:56     
connectivity in anatomical terms these     
13:58     
are known as anastamosis or connections     
14:02     
between two ramified regions of the     
14:05     
anatomy we can see this in zebra fish on     
14:07     
the lower left where you get cardiac     
14:09     
progenitor formation some cell migration     
14:12     
and fusion that results in a winar heart     
14:14     
tube and then chamber formation of the     
14:16     
heart later so you get this anatomical     
14:20     
transformation process whereby the cells     
14:22     
are be grouped into these tissues and     
14:25     
then they form these     
14:27     
structures and so this is an example of     
14:29     
an embodied hypergraph based Loosely on     
14:32     
seans embryogenesis it's not exactly     
14:35     
based on the lineage tree seans but it's     
14:37     
a demonstration and so what you have is     
14:40     
a single cell you start with a single     
14:42     
cell you have doubling events and so you     
14:46     
end up with this gray set of hypernodes     
14:49     
which are sort of the undifferentiated     
14:52     
cells very early on the germline     
14:54     
branches off and takes this yellow path     
14:58     
and then you have these other two paths     
14:59     
that emerge from the undifferentiated     
15:01     
cells at the 32 cell stage so these are     
15:04     
neural precursors and the embryo network     
15:07     
of somatic     
15:08     
cells what will become the somatic     
15:10     
phenotype and the neural connectone     
15:12     
respectively so the neural connectone is     
15:16     
basically cells that will become the     
15:18     
nervous system or the connectum and the     
15:21     
uh orange cells will become the body     
15:23     
outside the connective but each of these     
15:26     
cells form a network in of themselves as     
15:28     
we saw from from the embryo networks     
15:30     
earlier and of course we know that the     
15:31     
connectum forms its own network and the     
15:34     
question is as these cell types     
15:37     
differentiate you know what are the     
15:39     
connections between the connecto and the     
15:41     
phenotype and The Germ line and     
15:43     
everything else sometimes we expect     
15:45     
really sparse connections sometimes     
15:47     
things are totally modularized like The     
15:49     
Germ line and sometimes they're you know     
15:52     
you get cells that start off in one     
15:54     
category move to the other so you might     
15:57     
get cells that are sematic cells that     
15:59     
turn into neurons through some process     
16:02     
not seelan so much but in other     
16:04     
organisms you get this interchange of     
16:06     
cells from one category to another so     
16:08     
you see these connections between these     
16:10     
subgraphs of the     
16:14     
anatomy finally I'd like to talk about     
16:16     
mul's gso work and of course what he was     
16:19     
doing was building on our hypergraph     
16:22     
approach and trying to figure out how to     
16:25     
decompose seelan embryo spatio     
16:28     
temporarily so he built a number of     
16:30     
hypergraphs using algorithms and uh     
16:33     
other types of approaches uh on the left     
16:36     
you see the lineage hypergraph which is     
16:38     
based on the lineage tree data you have     
16:41     
these concentric circles which represent     
16:44     
the area around single cells that allow     
16:47     
you to sort of group different cells     
16:50     
into these hyper nodes so you have a     
16:53     
bunch of cells within each of these     
16:55     
circles and they're all connected in a     
16:57     
network     
16:58     
that's based on the lineage tree and     
17:00     
then on the right you have a spatial     
17:02     
hyper graph where the relationships are     
17:04     
based on the dis spatial distance     
17:06     
between cells so you can see it looks a     
17:07     
lot different the lineage hypergraph     
17:09     
looks like a radiating tree spatial     
17:12     
hypergraph looks like a bunch of     
17:13     
clusters in different places so that     
17:16     
makes     
17:17     
sense you can also do sort of spatio     
17:20     
temporal decomposition using DB scan     
17:22     
clustering techniques and so he did this     
17:25     
version where he did this applied this     
17:27     
algorithmic approach and tried to find     
17:30     
the nearest cells to you know in other     
17:33     
cells and you know determine these     
17:35     
clusters and these clusters then served     
17:37     
as the basis for these hypernodes the     
17:39     
hypernodes then being connected by     
17:42     
multiple edges which are collectively     
17:44     
known as Hyper edges and you have your     
17:46     
hyper     
17:48     
graph and so if we zoom in on this     
17:50     
spatio temporal decomposition we can see     
17:53     
that each of these cells have an an     
17:57     
identifier you know that we might see in     
17:59     
see elegan lineage tree and we see     
18:01     
clusters of these cells so that you get     
18:04     
these hyper nodes that are clustered as     
18:07     
well as the nodes themselves and their     
18:09     
connections so you can see that there's     
18:11     
this fine green structure of this hyper     
18:14     
graph and so we haven't really gotten to     
18:16     
the point where we can analyze the     
18:17     
hypergraphs yet but we can certainly     
18:20     
build them from data in a number of     
18:22     
sophisticated     
18:23     
ways so we zoom in even more and we can     
18:25     
see the nomenclature we can see that     
18:28     
relationship     
18:29     
and the sort of Criterion we're using     
18:31     
the concentric     
18:34     
circles so our weekly meetings continue     
18:37     
this year we usually meet on Mondays at     
18:39     
10:00 a.m. eastern time it's in North     
18:41     
America and so you're welcome to join     
18:44     
from anywhere on the world provided it's     
18:45     
not an inconvenient time for you we also     
18:49     
record our meetings and post them later     
18:50     
on YouTube so they're accessible     
18:53     
synos and we do all sorts of things in     
18:55     
these meetings we do topical reviews we     
18:57     
talk about biology ology we talk about     
19:00     
computation we do technological     
19:02     
tutorials and other things as well so I     
19:05     
have an archive on our GitHub site where     
19:08     
we have an archive of our meetings going     
19:10     
back to the beginning of 2020 so there's     
19:12     
a there are a lot of topics in these     
19:13     
meetings a lot of content to catch up on     
19:16     
and certainly you can I think find a lot     
19:19     
of interesting information in these     
19:22     
meetings so thank you to our     
19:24     
contributors for October 2023 to     
19:28     
November     
19:29     
24 Bradley ala Richard Gordon Susan     
19:33     
Crawford young Tom pores Jesse parent py     
19:37     
Balia mul Aurora Morgan Huff Lucas     
19:41     
bastani hu shogul bahid Gumi Hussein     
19:46     
ather harid Sharma Alexander Dale Luke     
19:50     
Noble sarra Kumar Roy Danel Paul GOI     
19:54     
swarup and S mon ready so they at least     
19:57     
attended one of our meetings it probably     
20:00     
did more but I wanted to observe     
20:02     
everyone who at least attended one     
20:04     
meeting and so you we'd like to grow our     
20:06     
community and you're welcome to join us     
20:09     
either attending a meeting or doing a     
20:11     
project or whatever and our topics are     
20:14     
very wide ranging so we've talked this     
20:16     
year about things ranging from multif     
20:18     
physics modeling to     
20:20     
tensegrity to biophysics to     
20:24     
developmental connectomics to sof soft     
20:27     
active materials Janice     
20:29     
phenomena swarms and Collective behavior     
20:33     
and cotons and differentiation     
20:35     
waves so thank you for your attention
