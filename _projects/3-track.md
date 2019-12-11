---
title: "Track: Generic logger backend for machine learning"
excerpt: "Track is a generic logger backend developed at Mila that can serve as a bridge between different logging libraries for machine learning. The goal is to provide a backend for Oríon so that users can use their own logger without any modification and simply configure Oríon to use the proper bridge with Track."
collection: projects
---

<b>Documentation</b> [track.readthedocs.io](https://track.readthedocs.io) <br/>
<b>Source code</b> [github.com/Delaunay/track](https://github.com/Delaunay/track)

Track is a generic logger backend developed at Mila that can serve as a bridge between different
logging libraries for machine learning. So far, this has been the work of [Pierre
Delaunay](https://github.com/delaunay) with whom I collaborated as a contributor of ideas and as a
reviewer. The goal is to provide a backend for [Oríon](/projects/1-orion) so that users can use
their own logger without any modification and simply configure Oríon to use the proper bridge with
Track. We built it outside of Oríon so that it can be used alone by users or reused in other
frameworks as well.
