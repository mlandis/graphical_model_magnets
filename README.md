## DIY Graphical Model Magnets: How To and some Why

Building a graphical model with magnets (DAGnets?)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="img/pgm_anim.gif" width="350px"/>

The magnets are simple, lightweight, and clean. When placed on a whiteboard, they make a satisfying "clack". Overall, rather fun to play with.

* Useful for teaching
* Design models anywhere ferrous
* Compact and organized storage
* Easy enough for a baby to use
  <br><img src="img/pgm_baby.jpg" width="350px"/>

Contact
* Email: [mlandis@gmail.com](mailto:mlandis@gmail.com)
* Twitter: [@landismj](https://twitter.com/landismj)

### Materials

I prototyped the design with cardboard cutouts to decide what size I liked. The below sizes are visible from about 40 feet away. These materials aim to balance cost and quality. About $40 was enough to build 20 nodes and 20 edges, with much of that being overhead from shipping:

- wooden shapes
  - circles, 3.5 inches wide [[link](https://www.etsy.com/listing/512797965/circle-shape-large-small-pick-size)]
  - squares, 3.5 inches wide [[link](https://www.etsy.com/listing/504579752/square-shape-large-small-pick-size)]
  - arrows (x2), 5.0 inches long [[link](https://www.etsy.com/listing/592074708/long-arrow-shape-large-small-pick-size)]
- small powerful magnets, 8x3mm [[link](https://www.amazon.com/gp/product/B07DD61G2F/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1)]
- adhesive dry erase contact paper, includes markers [[link](https://www.amazon.com/gp/product/B0784XN6Q4)]
- strong glue [[link](https://www.amazon.com/gp/product/B001L6CVS6)]
- black acrylic paint & brush (already had these)

### Assembly

After settling on the procedure, it took only 90 minutes of work to prepare all 20 nodes and 20 edges. Waiting for glue and paint to dry adds to the total time. Working in batches in a dedicated workspace speeds the process. Use cardboard in your workspace to protect your furniture from glue, paint, and knife scratches.

#### Nodes & Edges
  1. Mark the center of each shape
    <br><img src="img/pgm_node_mark.jpg" width="350px"/>
  2. Dab with glue
    <br><img src="img/pgm_node_glue.jpg" width="350px"/>
  3. Place magnet (match polarity across shapes)
    <br><img src="img/pgm_node_magnet.jpg" width="350px"/>
  4. Apply pressure until dry (prevents tilting of magnets)
    <br><img src="img/pgm_node_pressure.jpg" width="350px"/>

#### Nodes

  (Complete steps 1-4)
  
  5. Place node face down on to contact paper
    <br><img src="img/pgm_node_paper.jpg" width="350px"/>
  6. Trim edges with a fine, sharp edge
    <br><img src="img/pgm_node_trim.jpg" width="350px"/>

#### Edges
  
  (Complete steps 1-4)
  
  5. Listen to appropriate [music](https://youtu.be/5wCUlPNlQuA?t=7s) (optional)
  6. Paint it black
    <br><img src="img/pgm_edge_paint.jpg" width="350px"/>
   
#### Done

- And that's it!
<br><img src="img/pgm_done.jpg" width="350px"/>
  
### Motivation

Probabilistic models are sets of random variables that share a common dependency structure. Such models have an equivalent graphical representation, in which model variables are represented by nodes and and variable dependencies are represented by directed edges. These graphs are called probabilistic graphical models (PGMs). PGMs are useful in modeling for many purposes: from designing efficient algorithms for inference methods, to blueprinting and specifying models, to teaching and communicating how particular models are built.

I study evolutionary biology. A major part of my research involves developing methods for the Bayesian phylogenetics package, [RevBayes](http://revbayes.com). In RevBayes, both the scripting language that biologists use to specify models and the computational back-end that's used for inference are designed upon a graphical architecture (papers for the [software](https://academic.oup.com/sysbio/article/65/4/726/1753608) and its underlying [design](https://academic.oup.com/sysbio/article/63/5/753/2847897)).

When I'm not developing RevBayes code, I use RevBayes to explore evolutionary models to understand how life evolved on the planet (examples of recent work studying [turtle](https://academic.oup.com/sysbio/article/66/2/128/2669985) and [silversword](https://www.biorxiv.org/content/early/2018/04/17/301887) biogeography). A major part phylogenetic research requires prototyping and designing new models. Similar to how programmers write pseudocode to first sketch out the logical skeleton of unwritten code, I sketch graphical models to initially design the logical skeleton of my model.

Drawing PGMs to this end is clarifying, and even fun, whether by hand or using graphing software like [TikZ](https://sourceforge.net/projects/pgf/). But as model complexity grows, so does the model's graphical representation. On particularly uninhibited days, constructing a PGM without prudent urban planning may result in a graph that no longer fits on the board, becomes lopsided, etc. Redistributing the layout of nodes and edges generally means erasing and redrawing large portions of your graph -- perhaps multiple times, depending on how careful you are when brainstorming. That's mostly a personal problem, but one others might share.

More broadly, I've taught at the [Molecular Evolution Workshop](https://molevol.mbl.edu/index.php/Main_Page) in Woods Hole for the past few years. With others, I teach portions of the [Bayesian phylogenetics](https://revbayes.github.io/workshops/woodshole2018.html) unit, where I introduce concepts in phylogenetic model building while using RevBayes as a platform. My presentation normally relies on either static premade images or hand drawn board work. While imagining more effective ways to present the material, magnets came to mind -- magnets where you could write on their surface and rearrange them in whatever way the group's curiosity might take us. I thought magnets like this might be available online, but my searches came up empty. So the only thing to do was to make some myself!

The magnets made for a fantastic teaching aid -- e.g. "Who'll volunteer to build the graphical model that specifies such-and-such list of equations? How many random variables do you have? How many edges are needed? What if you treated the value of U to be determined by the function L + z^2 instead of as a constant value? What if you set z to be Gamma-distributed with shape 2 and scale 4?" -- it turned what could have been a stale moment into something lively and interactive that involved the whole class.

I'm more than pleased with how the graphical model magnets turned out. And the students and teachers at the workshop seemed to enjoy them, too. My thanks go to the MolEvol2018 [Course Participants](https://molevol.mbl.edu/index.php/Participants) for allowing [Tracy Heath](http://phyloworks.org/) and myself to try these out in the classroom! Besides teaching, I'm finding the magnets are a pleasant alternative to pen-and-paper for diagramming new models.
  
### Ideas for improvements

There are a few ways to improve the design with additional materials and effort:

- Rather than using one central magnet, using 2--4 weaker magnets would improve stability of nodes and arrows against the board. Gouging spaces to embed magnets into the wooden shapes would also help stabilize the markers and improve how well the glue binds to the magnet.
- Adding magnetized connectors to nodes and edges so that they "snap" together would be very satisfying. Eliminating the need to match arbitrary polarities for connections seems like it'd require some clever (but thrifty) engineering.
- Painting permanent borders on to the nodes might give them a cleaner look, though I like that I can define the node's identity on the fly (e.g. stochastic vs. deterministic nodes). Permanently dyeing a few circular (stochastic) nodes gray for use as observed stochastic nodes would also be a nice touch. The directed edges could use a coat of sealant.
- Currently the edges are short and rigid, which could be a problem when longer or crossed edges are needed in complex graphs. As a hack, stacking extra magnets to the back of some edges would allow for crossing. Longer or curved arrows could be purchased through Etsy at higher cost (custom shapes).
