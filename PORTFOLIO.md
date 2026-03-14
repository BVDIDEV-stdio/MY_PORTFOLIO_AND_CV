## Portfolio
### Thesis Paper and Graduation Project
As my graduation project I developed Unity game prototype to showcase the skills I acquired over four years of study. The prototype features a scene that includes:
- **Player character** capable of running, jumping, attacking and performing combo attacks, as well as shooting a projectile as a secondary attack;
- **Enemy character** that can patrol its surroundings or rapidly approach the player to attack; (enemy behaviour reminds that of Holow Knight basic enemies)
- healing mechanics and healing items logic
The project was designed with a focus to minimize component dependencies, ensuring modularity and scalability. The approach allows for easy improvements and reworking certain mechanics without overhauling the entire game code.


<div>
  <img src="/thesis_scheme_1.png" width="400" alt="на этой пикче общая схема логики игрового персонажа"/>
  <img src="/thesis_scheme_2.png" width="400" alt="тут схема противника"/>
  <img src="/thesis_scheme_3.png" width="400" alt="тут схема работы UI"/>
</div>
<p><em>Diagrams for: player character components and their interaction; Enemy AI logic and composition; UI logic</em></p>


<div>
  <img src="/thes_blender_skeletal_anim.png" width="400" alt="тут перс в блендере создаётся"/>
</div>
<p><em>Models and animations were made from scratch to cover basic visual requirements. Visual fidelity was not a priority, of course</em></p>


<div>
  <img src="/thes_animtree_combo.png" alt="пикча с анимациями для комбо"/>
</div>
<p><em>Anim state machine, providing combo-attacks on consecutive button clicks</em></p>

<div>
  <img src="/thes_anim_states.png" alt="ещё пикча с анимационным state machine"/>
</div>
<p><em>Anim state machine featuring player character logic in general</em></p>
<div>
  <img src="/thes_ui_1.png" width="400" alt="UI 1"/>
  <img src="/thes_ui_2.png" width="400" alt="UI 2"/>
</div>
<p><em>Examples for basic UI</em></p>

YouTube: https://youtu.be/yQFOX5VP178
Github: https://github.com/BVDIDEV-stdio/THESIS_WORK

### A small Snippet Project - Unreal Engine
https://youtu.be/MTQOhWPwzuw
The snippet project feature modular character system as well as an animation rig enhanced with leg IK so they align on slopes and uneven surfaces.
### 3D art
<div>
  <img src="/SHOTGUN_STYLIZED.png" width="500"/>
  <img src="/SHOTGUN_STYLIZED_2.png" width="500"/>
</div>
<p><em>Stylized futuristic shotgun practice, old work</em></p>

<div>
  <img src="/mp_styl.png" width="300"/>
  <img src="/mp_styl_2.png" width="300"/>
</div>
<p><em>Stylized MP5 practice, old one too</em></p>

<div>
  <img src="/port_arm.png" width="240"/>
  <img src="/port_char.png" width="240"/>
</div>
<div>
  <img src="/port_char2.png" width="240"/>
  <img src="/port_char3.png" width="240"/>
</div>
<div>
  <img src="/port_char4.png" width="240"/>
</div>
<p><em>Minimalistic character practice</em></p>

<div>
  <img src="/study_columns.png" width="300"/>
  <img src="/study_spike_n_arc.png" width="300"/>
  <img src="/scr_team_work1.png" width="300"/>
  <img src="/scr_team_work2.png" width="300"/>
</div>
<p><em>Some of the models created as part of a team project (top-down stealth action) for my master's program</em></p>

<div>
  <img src="/sawd_off1.png" width="300"/>
  <img src="/sawd_off2.png" width="300"/>
</div>
<p><em>Stylized sawed-off shotgun for a pet project of mine</em></p>





### Test Assignment : (b)race yourself 
[*see repo*](https://github.com/BVDIDEV-stdio/ghost-task)

A mini-project I made as an assignment from a potential (not anymore) employer. So it ends up in my portfolio, why not.

**Gameplay**
- First run: the player casually drives through the route. Their movements are real-time recorded during this run.\
![Bruh gif gone](/gif1.gif)
- Second run: the player competes a "ghost" car that replays the exact movements from their first run, allowing them to race against their own previous performance. \
![Bruh this one gone too](/gif.gif)

**Features**
- *Input Recording* is as precise as Rigidbody (and I guess physics engine) calculations are. Input record is called in Update exactly because it records a rigidbody-using "pawn" (car);
- *Input Replay* simply passes input commands into controller - like if player would do. This was made possible thanks to input-reading interface that both *player input class* and *input  replay class* derive from. Of course had to tweak SimCadeVehicleController a little to support input-transmitting classes, as well as new InputSystem;
- CineMachine camera transitions

### Test Assignment : Crane VR Training
[*see repo*](https://github.com/BVDIDEV-stdio/TestAssignment-vr-crane-gasAnalyzer)
**Gameplay**
- Features a controllable overhead crane. Each degree of freedom and direction (girder, hoist and hook block height) is controlled separately.
- "Gas analyzer": a compound device. A display and a sensor connected with cable. Display is to show distance between "closest danger" and the sensor. The device can be enabled or disabled. A spinning dog on the loading screen - absolutely necessary.
[[pics underway]]

### Pet project
*//repo is private*
Is on game design stage. No code demonstrated via repo link since it's not final - defining system flows should be carried out first. Current code is clean enough for a proto - I practiced on it to keep my skills sharp.
[[gifs underway]]
Code: Inventory system done, hitscan guns + visual feedback done. Ammo spending via shot and reload done. UI base window class done.

Project game design mainly focuses on a simple CRPG-system support and FPS battle-core.
