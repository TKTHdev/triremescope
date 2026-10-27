# TriremeScope

An interactive, in-browser model of the Trireme weighted leaderless consensus protocol at t = 1, in the spirit of RaftScope.

Live page: https://tkthdev.github.io/triremescope/

Move the hot client site, crash and restart replicas, and watch ADAPT compute the aggregated latency cost (ALC) of each thranite placement, accumulate the latency gap against the switching cost, and issue a RESEAT that moves the heavy weights toward the load.

This is a teaching model. RTTs are illustrative, map positions are schematic, and several protocol details are simplified; the page lists every simplification.
