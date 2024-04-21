The Process
===========

Many believe that the game development process includes three major phases: **Pre-Production**, **Production**, and **Post-Production**. (YoYo Games, n.d.) shows the production lifecycle as actually containing **seven**, saying only having three phases as a bit of an oversimplification. At |Studio|, we follow this seven-stage process. 

.. mermaid::

    flowchart LR
            Planning("Planning")
            PreProd("Pre-Production")
            Prod("Production")
            Testing("Testing")
            PreLaunch("Pre-launch")
            Launch("Launch")
            PostLaunch("Post-launch")
            subgraph "Pre-Production"
            Planning --> PreProd
            end
            PreProd --> Prod
            subgraph "Production"
            Prod --> Testing
            Testing --> PreLaunch
            PreLaunch --> Launch
            end
            subgraph "Post-Production"
            Launch --> PostLaunch
            end

Planning
--------
As the very first stage of the development lifecycle, the Planning phase is where the foundation is created. In this phase, we answer all of the critical questions for the game, such as the genre of the game, the artistic styling, story, game engine, mechanics, etc. These are the fundamentals that should be determined before any development takes place, as making changes to these fundamentals after development starts can be very costly. 

In the Planning phase, we will also produce a proof of concept. The proof of concept is useful for understanding the time it will take to develop the project, the cost, the skills needed, and much more. It also gives a chance to demo to the game to interested parties.

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - 
     - Proof of Concept
   * - 
     - Game Development Journal
   * - 
     - Game Design Document Initial Draft

Pre-Production
--------------
Now that the project is better understood, the work can be scoped out. Several critical roles exist to ensure that the project stays on track:

* **Artist**: Ensures that the game's theme and genre matches that of what was determined in the Planning phase.
* **Developer**: Determines the mechanics, physics, and other core aspects of how the game will work.
* **Engineer**: Determines the limitations that the project will have, such as the computation limitations if the game will be made for mobile or console. 
* **Project Lead**: Keeps the progress of the project moving forward by communicating across all teams, making compromises that ultimately lead to a better project.
* **Writers**: Create the script and story for the project.

With all of the roles and responsibilities, it is important to remain flexible during the Pre-Production phase.

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - Proof of Concept
     - Prototypes
   * - Game Development Journal
     - Updated Game Development Journal
   * - Game Design Document Initial Draft
     - Updated Game Design Document

Production
----------
In this longest phase of the project's lifecycle, the majority of the project will be developed. All mechanics will be implemented, levels designed, sounds recorded, and much more. The project comes to life in this phase.

During production, some decisions may need to be made in order to keep the project on track, both from a timeline perspective and a thematic. 

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - Game Development Journal
     - Updated Game Development Journal
   * - Game Design Document Initial Draft
     - Updated Game Design Document

Testing
-------
The testing phase is one of the most important phases of the development lifecycle. Here, we search for bugs and exploits that may have made their way in during development. 

During testing, we also look at the playability and the "funness" of the game. While this is a secondary part of the testing phase, it is worth evaluating the feedback from testers.

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - Project Alpha Release
     - Stable Project Beta Release
   * - Test Plan
     - Test Results

Pre-Launch
----------
With a stable beta-release, the project can be marketed and presented to the public. Demos can be delivered and feedback solicited. The reception of the project will be unknown, but this is a vital phase of the process, as it is how the world finds out about the game.

Based on the feedback, changes can still be made to the project to incorporate that feedback and lead to a better, more desired game.

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - Stable Project Beta Release
     - Refined Project Beta Release

Launch
------
In the Launch phase, we can polish the project. This may mean squashing any last bugs or refining the visual quality. 

.. list-table:: Inputs and Outputs
   :header-rows: 1

   * - Inputs
     - Outputs
   * - Refined Project Beta Release
     - Project Release
   * - 
     - Finalized Game Design Document

Post-Launch
-----------
In the Post-Launch phase, the project has been deployed and will not be maintained. Here we can provide bug fixes that may have been missed during development, add content via DLCs, or other patches.

.. list-table:: Inputs and Outputs
   :header-rows: 1
   
   * - Inputs
     - Outputs
   * - Project Release
     - Project Next Revision
   * - 
     - Project DLC

References
----------
1. YoYo Games. (n.d.). What are the main stages of game development? | GameMaker. GameMaker. https://gamemaker.io/en/blog/stages-of-game-development


.. Variables
.. |Studio| replace:: Sinclair Games