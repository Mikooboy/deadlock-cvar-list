Name | Flags | Description
---- | ----- | -----------
+chatwheel | cl, release | Opens chatwheel menu while held
+chatwheel_pingwheel | cl, release | Opens the second chatwheel menu while held
+citadel_swtich_player_cam | cl, release | Player Cam switching button pressed
+herochatwheel | cl, release | Opens hero chatwheel menu while held
+in_ability_ping | cl, release | Ping button pressed
-chatwheel | cl, release | Executes the highlighted chatwheel menu item
-chatwheel_pingwheel | cl, release | Executes the highlighted chatwheel menu item
-citadel_swtich_player_cam | cl, release | Player Cam switching button released
-herochatwheel | cl, release | Executes the highlighted hero chatwheel menu item
-in_ability_ping | cl, release | Ping button released
Test_CreateEntity | sv, cheat | 
Test_EHandle | sv, cheat | 
Test_ExitProcess | cheat | Test_ExitProcess &lt;exit code&gt; - immediately kill the process.
Test_RandomPlayerPosition | sv, cheat | 
_record | cheat, norecord, release | Record a demo incrementally.
adsp_debug | a | Default: 0<br>
ai_debug_decisionmaking | sv, a | Default: false<br>Draw sparks on NPCs in their thinks. Sparks at their feet mean they skipped decision making, sparks high above them means they didn't.
ai_debug_dyninteractions | sv, cheat | Default: 0<br>Debug the NPC dynamic interaction system.
ai_debug_enemy_position | sv, cheat | Default: false<br>Draw a debug line from a selected NPC to its enemy.
ai_debug_los | sv, cheat | Default: 0<br>NPC Line-Of-Sight debug mode. If 1, solid entities that block NPC LOC will be highlighted with white bounding boxes. If 2, it'll show non-solid entities that would do it if they were solid.
ai_debug_scripted_sequence | sv, cheat | Default: false<br>
ai_debug_shoot_positions | sv, cl, rep, cheat | Default: 0<br>
ai_debug_squadslotusage | sv, cheat | Default: false<br>Report squad slot usage for npc_selected NPCs.
ai_disable | sv, cheat | Bi-passes all AI logic routines and puts all NPCs into their idle animations.  Can be used to get NPCs out of your way and to test effect of AI logic routines on frame rate
ai_disabled | sv, cl, rep, cheat | Default: false<br>
ai_drop_hint | sv, cheat | Drop an ai_hint at the player's current eye position.
ai_facingservices_debug_reasonablefacing | sv, cheat | Default: 0<br>Debug logic for finding reasonable facing.
ai_facingservices_debug_spew | sv, cheat | Default: false<br>Adds spew to the facing target for the selected NPC
ai_facingservices_draw_entity_facing | sv, cheat | Default: false<br>
ai_ignore_collision_player_noclip | sv, a, cheat | Default: false<br>
ai_inhibit_spawners | sv, cheat | Default: false<br>
ai_keep_interrupt_path_across_schedules | sv, cheat | Default: true<br>
ai_motor_debug | sv, cheat | Default: 0<br>
ai_motor_debug_additional_movement_settings | sv, cheat | Default: false<br>
ai_motor_debug_ag1_path | sv, cheat | Default: false<br>
ai_motor_debug_hop | sv, cheat | Default: false<br>
ai_motor_debug_idle_turn | sv, cheat | Default: false<br>
ai_motor_debug_move_heading | sv, cheat | Default: false<br>
ai_motor_debug_move_heading_bad_zones | sv, cheat | Default: false<br>
ai_motor_debug_override_path | sv, cheat | Default: false<br>
ai_motor_debug_show_current_state | sv, cheat | Default: false<br>
ai_motor_debug_show_speed_info | sv, cheat | Default: false<br>
ai_motor_debug_state_deadlocks | sv, cheat | Default: false<br>
ai_motor_debug_stop | sv, cheat | Default: false<br>
ai_motor_debug_transitions | sv, cheat | Default: false<br>
ai_motor_enable_move_heading_bad_zones | sv, cheat | Default: true<br>
ai_motor_max_state_time_active | sv, cheat | Default: 6<br>
ai_motor_move_direction_lookahead | sv, cheat | Default: 6<br>
ai_motor_nav_links_force_facing_time | sv, cheat | Default: 12<br>
ai_motor_path_alignment_max_angular_velocity | sv, cheat | Default: 300<br>
ai_motor_planted_turn_lookahead_distance | sv, cheat | Default: 100<br>
ai_motor_planted_turn_lookahead_distance_speed | sv, cheat | Default: 150<br>
ai_motor_procedural_idle_turn_speed | sv, cheat | Default: 20<br>
ai_motor_procedural_idle_turn_threshold | sv, cheat | Default: 2<br>
ai_motor_procedural_turn_while_stopping_threshold | sv, cheat | Default: 5<br>
ai_motor_use_fast_move_heading_bad_zone_pass | sv, cheat | Default: true<br>
ai_navigator_disable_collision_on_stuck | sv, cheat | Default: true<br>
ai_navigator_repath_enable | sv, cheat | Default: true<br>Enable dynamic repathing based on goal movement.
ai_navigator_repath_on_change | sv, cheat | Default: true<br>When nav mesh changes along an NPC's existing path, force a repath.
ai_navigator_repath_tolerance_alpha | sv, cheat | Default: 20<br>The distance a target entity can move before triggering a repath is ( arrival time * ai_navigator_repath_tolerance_alpha ), clamped to the min / max allowed values.
ai_navigator_repath_tolerance_max | sv, cheat | Default: 300<br>The maximum distance that a target entity can move before triggering a repath to that target.
ai_navigator_repath_tolerance_min | sv, cheat | Default: 8<br>The minimum distance that a target entity can move before triggering a repath to that target.
ai_navigator_repath_tolerance_min_speed | sv, cheat | Default: 100<br>When calculating repathing tolerance, clamp entity speed to be at least this value (i.e. consider slow entities to be this fast).
ai_navigator_snap_to_ground_goal | sv, cheat | Default: false<br>
ai_navigator_use_arrival_direction | sv, cheat | Default: true<br>
ai_off_nav_show_nearest | sv, cheat | Default: false<br>
ai_path_show_discard_immediately | sv, cheat | Default: false<br>
ai_report_task_timings_on_limit | sv, a | Default: false<br>
ai_resume | sv, cheat | If NPC is stepping through tasks (see ai_step ) will resume normal processing.
ai_select_box_alpha | sv, a | Default: 20<br>The select box alpha.
ai_setenabled | sv, cheat | Like ai_disable but you manually specify the state (with a 0 or 1) instead of toggling it.
ai_show_hints | sv, cheat | Displays all hints as small boxes<br>	Blue		- hint is available for use<br>	Red		- hint is currently being used by an NPC<br>	Orange		- hint not being used by timed out<br>	Grey		- hint has been disabled
ai_show_task_fail | sv, cheat | Default: 0<br>
ai_step | sv, cheat | NPCs will freeze after completing their current task.  To complete the next task, use 'ai_step' again.  To resume processing normally use 'ai_resume'
ai_temp_difference_for_instant_ignite | sv, cheat | Default: 100<br>how much hotter than the npc's flashpoint a heat source should be to instantly ignite them.
ai_think_limit_label | sv, a | Default: false<br>
ai_time_to_ignite | sv, cheat | Default: 0.3<br>How long an npc has to be exposed to heat above their flashpoint to catch on fire.
ai_vehicle_avoidance | sv, cheat | Default: true<br>
alias | release | Alias a command.
anim_resource_validate_on_load | release | Default: true<br>Validates the animation group channel list against the animations on load for every animation
animated_material_attributes | cl, cheat | Default: true<br>
animevents_dump | sv, cheat | List all the currently registered anim events.<br>
animgraph_debug | sv, cl, rep, cheat | Default: false<br>Debug animation graph
animgraph_debug_entindex | sv, cl, rep, cheat | Default: 0<br>The entity to specifically debug
animgraph_debug_max_poseop_count |  | Default: false<br>
animgraph_footlock_ik_enable | rep, cheat | Default: true<br>Enable IK.
animgraph_record_all | sv, cl, rep, cheat | Default: false<br>Automatically start recording AnimGraphs when they get created, and save them to disk when they are destroyed
animgraph_slope_draw_raycasts | sv, cl, rep, cheat | Default: false<br>
animgraph_slope_enable | sv, cl, rep, cheat | Default: false<br>
animgraph_trace_static_only | sv, cl, rep, cheat | Default: false<br>
announce_create | cl, release | &lt;title&gt; &lt;message&gt; &lt;URL&gt; \[Priority\] Create a new announcement with the specified title, message, and URL. use empty quotes if you want to skip message or URL
announce_delete | cl, release | &lt;ID&gt; Deletes the specified announcement ID
announce_show_ids | cl, release | Default: false<br>When set, will show the IDs of the various announcements, making updating/deleting easier
announce_update | cl, release | &lt;ID&gt; &lt;title&gt; &lt;message&gt; &lt;URL&gt; \[Priority\] Create a new announcement with the specified title, message, and URL. use empty quotes if you want to skip message or URL
audio_display_soundstack_debug_base_3d | sv, cheat | Default: false<br>Displays citadel_base_3d sound stack debug.
audio_display_soundstack_debug_dialog | sv, cheat | Default: false<br>Displays citadel_dialog sound stack debug.
audio_enable_vmix_mastering | cl, cheat | Default: true<br>Enables mastering DSP in vmix.
audio_health_change_damage_priority_threshold | cl, cheat | Default: -0.02<br>Above this health fraction change damage audio is deprioritized in the sound system.
audio_log_damage_recency_bias | sv, cheat | Default: false<br>Prints player damage recency information.
audio_voice_volume_protection | cl, cheat | Default: 2<br>Sets linear scale volume limit for SOS.
automatically_open_saved_animgraph_recording | sv, cl, a, rep | Default: false<br>
axis | sv, cheat | Draw an axis<br>	Arguments:  x y z pitch yaw roll &lt;lifetime = 10.0&gt; &lt;r g b a&gt;<br>
ban_ignore_after_player_abandons | sv, cheat | Default: 1<br>After this many players have abandoned a match, no longer penalize additional abandons for the match. Set to 0 to not penalize abandoners
battery_saver | a | Default: false<br>OBSOLETE replaced by mobile_fps_* - Battery saver mode. 0=off, 1=on
benchframe | release | Takes a snapshot of a particular frame in a time demo.
bind | release | Bind a key.
binddefaults | release | Bind all keys to their default values.
bindss | release | Bind a key for a particular splitscreen player.
bot_kick_all | sv, cheat | Kick all the bots
bot_mimic | sv, cl, rep, cheat, release | Default: 0<br>Allows bots to mimic player
bot_mimic_spec_buttons | cl, cheat | Default: true<br>+attack, +jump etc are used for spectator control instead of being passed on to spectated bot
bot_mimic_target | sv, cheat | Selects the targeted bot for mimicking
bot_mimic_yaw_offset | sv, cheat | Default: 180<br>Offsets the bot yaw.
bot_puppet | sv, cl, rep, cheat, release | Default: 0<br>Allows bots to be puppeteered by the player.  The player will do nothing while the bots perform the inputs
bot_puppet_target | sv, cheat | Selects the targeted bot for puppeteering
bot_record_target | sv, cheat | Selects the targeted bot for puppeteering
box | sv, cheat | Draw a bbox<br>	Arguments:  minx miny miny maxx maxy maxz &lt;lifetime = 10.0&gt; &lt;r g b a&gt;<br>
buddha | sv, nf, cheat | Default: false<br>Player takes damage but won't die
buddha_ignore_bots | sv, nf, cheat | Default: false<br>Bots always buddha 0
buddha_reset_hp | sv, nf, cheat | Default: 1<br>HP to set when damaged below zero in Buddha Mode
bug_submitter_override | a | Default: <br>
bullet_tracer_path_debug | cl, cheat | Default: 0<br>Debug: visualization time for bullet tracer particles (0 = disable)
button_info | release | Display information about the specified key or button.
c_maxdistance | cl, a | Default: 200<br>
c_maxpitch | cl, a | Default: 90<br>
c_maxyaw | cl, a | Default: 135<br>
c_mindistance | cl, a | Default: 30<br>
c_minpitch | cl, a | Default: 0<br>
c_minyaw | cl, a | Default: -135<br>
c_orthoheight | cl, a | Default: 100<br>
c_orthowidth | cl, a | Default: 100<br>
c_thirdpersonshoulder | cl, a | Default: false<br>
c_thirdpersonshoulderaimdist | cl, a | Default: 120<br>
c_thirdpersonshoulderdist | cl, a | Default: 40<br>
c_thirdpersonshoulderheight | cl, a | Default: 5<br>
c_thirdpersonshoulderoffset | cl, a | Default: 20<br>
cam_collision | cl, a | Default: 1<br>When in thirdperson and cam_collision is set to 1, an attempt is made to keep the camera from passing though walls.
cam_command | cl, cheat | Tells camera to change modes
cam_idealdelta | cl, a | Default: 4<br>Controls the speed when matching offset to ideal angles in thirdperson view
cam_idealdist | cl, a | Default: 150<br>
cam_ideallag | cl, a | Default: 4<br>Amount of lag used when matching offset to ideal angles in thirdperson view
cam_idealpitch | cl, a | Default: 0<br>
cam_idealyaw | cl, a | Default: 0<br>
cam_showangles | cl, cheat | Default: false<br>When in thirdperson, print viewangles/idealangles/cameraoffsets to the console.
cam_snapto | cl, a | Default: false<br>
camortho | cl, cheat | Switch to orthographic camera.
cast_aabb | sv, cheat | Tests box collision detection
cast_capsule | sv, cheat | Tests capsule collision detection
cast_convex | sv, cheat | Tests convex hull collision detection
cast_cylinder | sv, cheat | Tests cylinder collision detection
cast_intervals | sv, cheat | Tests interval ray cast
cast_obb | sv, cheat | Tests cylinder collision detection
cast_physics | sv, cheat | Tests physics shape collision detection
cast_ray | sv, cheat | Tests ray cast
cast_sphere | sv, cheat | Tests sphere cast
cc_delay_time | cl, a | Default: 0.25<br>Close caption delay before showing caption.
cc_lang | cl, a | Default: <br>Current close caption language (emtpy = use game UI language)
cc_linger_time | cl, a | Default: 1<br>Close caption linger time.
cc_spectator_only | cl, a | Default: false<br>
cc_subtitles | cl, a | Default: false<br>If set, don't show sound effect captions, just voice overs (i.e., won't help hearing impaired players).
cc_vr_caption_speed | cl, a | Default: 1<br>0 = slow, 1 = medium (default), 2 = fast
cc_vr_font_size | cl, a | Default: 1<br>0 = small, 1 = med (default), 2 = large
cc_vr_width | cl, a | Default: 1<br>0 = narrow, 1 = med (default), 2 = wide
changelevel | release | changelevel &lt;mapname&gt; :Multiplayer change level.
citadel_1v1_bonus_health | sv, cl, rep, cheat | Default: 0<br>
citadel_1v1_bonus_health_regen | sv, cl, rep, cheat | Default: 0<br>
citadel_1v1_bonus_tech_power | sv, cl, rep, cheat | Default: 0<br>
citadel_1v1_bonus_weapon_power | sv, cl, rep, cheat | Default: 0<br>
citadel_1v1_bullet_damage_multiplier | sv, cl, rep, cheat | Default: 1<br>
citadel_1v1_tech_damage_multiplier | sv, cl, rep, cheat | Default: 1<br>
citadel_ability_cooldown_max | sv, cl, rep, cheat | Default: 0<br>
citadel_ability_debug | sv, cl, rep, cheat | Default: false<br>
citadel_ability_preview_path_debug_draw_dt | cl, a | Default: 0.075<br>DT for debug drawing ability preview path.
citadel_ability_target_debug | sv, cl, rep, cheat | Default: 0<br>
citadel_ability_target_use_head_bone | sv, cl, rep, cheat | Default: false<br>
citadel_activate_cps_for_team | sv, cheat | Makes the CPs for a team available to capture
citadel_activate_window_for_pregame | cl, release | Default: false<br>If set, brings Citadel to the foreground when unpaused
citadel_activate_window_on_unpause | cl, a, release | Default: false<br>If set, brings Citadel to the foreground when unpaused
citadel_active_lane | sv, cl, rep, release | Default: 0<br>Which lane should be active? 0 means all
citadel_air_drag_min | sv, cl, rep, cheat | Default: 0.2<br>
citadel_aircontrol_speed_fast | sv, cl, rep, cheat | Default: 50<br>
citadel_aircontrol_speed_slow | sv, cl, rep, cheat | Default: 80<br>
citadel_allow_ally_pings | cl, a, release | Default: true<br>
citadel_allow_ally_text | cl, a, release | Default: true<br>
citadel_allow_ally_voice | cl, a, release | Default: true<br>
citadel_allow_client_higher_version_for_reconnect | cl, release | Default: true<br>When set to true, the client is allowed to connect so long as the client compat version is higher than the server's
citadel_allow_duplicate_heroes | sv, cl, rep, release | Default: false<br>If enabled, heroes can be selected by multiple players
citadel_allow_opponent_text | cl, a, release | Default: true<br>
citadel_allow_party_pings | cl, a, release | Default: true<br>
citadel_allow_party_text | cl, a, release | Default: true<br>
citadel_allow_party_voice | cl, a, release | Default: true<br>
citadel_allow_playofthegame | sv, cl, rep, cheat, release | Default: false<br>If enabled, play of the game will happen
citadel_allow_purchasing_anywhere | sv, cl, rep, cheat | Default: false<br>If enabled, you can purchase upgrades anywhere
citadel_allow_spectated_pings | cl, a, release | Default: true<br>
citadel_allow_spectated_text | cl, a, release | Default: true<br>
citadel_always_show_active_hud_stats | cl, a | Default: false<br>
citadel_assume_pawn_control | sv, cheat | Take control of the pawn under the crosshair, or by name if specified
citadel_auto_highlight_seconds_after | cl, release | Default: 8<br>How many seconds after the highlight event to show when viewing highlights.
citadel_auto_highlight_seconds_before | cl, release | Default: 20<br>How many seconds before the highlight event to show when viewing highlights.
citadel_auto_queue_build | cl, a, user | Default: false<br>Automatically queue the selected build at game start
citadel_ban_account | cl, release | 
citadel_ban_account_aim_assist | cl, release | 
citadel_ban_account_movement_assist | cl, release | 
citadel_ban_account_vision_assist | cl, release | 
citadel_book_open | cl, release | \[BookID/Book Name\] Opens up the specified book by ID or name
citadel_boss_glow_disabled | cl, release | Default: false<br>
citadel_boss_tier_3_testing_enter_phase2 | sv, cheat, release | Default: false<br>
citadel_boss_tier_3_testing_reset | sv, cheat | Respawns the boss
citadel_bot_attack_enemies |  | 
citadel_bot_brain_aim_angle_attack | sv, rep, release | Default: 0.9<br>Min Dot Product result from target that we will try to shoot from
citadel_bot_brain_aim_inaccuracy | sv, rep, release | Default: 0<br>Max Angle for Inaccuracy
citadel_bot_brain_aim_inaccuracy_speed | sv, rep, release | Default: 0.01<br>How fast the inaccuracy moves - mimic mouse movement correction
citadel_bot_brain_aim_vertical_offset | sv, rep, release | Default: 0<br>How many vertical units to aim from world space center on players / troopers
citadel_bot_brain_disable_attacks | sv, rep, release | Default: false<br>
citadel_bot_brain_disable_gun_attacks | sv, rep, release | Default: 0<br>
citadel_bot_brain_disable_movement | sv, rep, release | Default: false<br>
citadel_bot_brain_enemy_reaction_time | sv, rep, release | Default: 0.75<br>Amount of time for a bot to react to a player
citadel_bot_brain_heavy_melee_distance | sv, rep, release | Default: 300<br>
citadel_bot_brain_infrequent_tick_rate | sv, rep, release | Default: 60<br>
citadel_bot_brain_melee_heavy_hold_time | sv, rep, release | Default: 0.31<br>
citadel_bot_brain_melee_tick_frequency | sv, rep, release | Default: 30<br>
citadel_bot_brain_move_goal_tolerance | sv, rep, release | Default: 40<br>How close to goal to count as made it
citadel_bot_brain_move_max_fallback_path_length | sv, rep, release | Default: 1750<br>If a bot fails its (fast) flowmap check, how far should we allow the nav system to look when generating a fallback path? Keep this value lower for performance reasons
citadel_bot_brain_override_calc_movement_task_target | sv, rep, release | Default: false<br>Override CalcMovementTaskTarget to pathfind directly to the desired location as opposed to an intermediate goal
citadel_bot_brain_parry_tick_frequency | sv, rep, release | Default: 20<br>
citadel_bot_brain_stop_shooting_los_time | sv, rep, release | Default: 0.5<br>Amount of time for no Los to stop shooting at enemy
citadel_bot_buddy | sv, cl, rep, release | Default: <br>List of heroes to choose from that should follow a player around
citadel_bot_crouch | sv, rep, release | Default: false<br>Forces citadel bots to crouch
citadel_bot_give_team_gold | sv, cheat | Give all bots on a particular team gold
citadel_bot_hero_testing_pitch | sv, rep, release | Default: 5<br>Aim Pitch in Hero Testing
citadel_bot_jump | sv, rep, release | Default: false<br>Forces citadel bots to jump
citadel_bot_list_ents | sv, cheat | List ent id of all players that are bots in this game
citadel_bot_list_objectives_ent | sv, cheat | List all entities that are associated with a Citadel Game Objective
citadel_bot_melee | sv, rep, release | Default: 0<br>Forces citadel bots to melee continuously, 1: light, 2:Heavy
citadel_bot_mimic_player_pitch | sv, rep, release | Default: true<br>User player's pitch in hero testing
citadel_bot_move_random | sv, rep, release | Default: false<br>Forces citadel bots to move all around
citadel_bot_parry | sv, rep, release | Default: false<br>Forces citadel bots to Parry continuously
citadel_bot_playrecording | sv, cheat | Play back commands recorded via 'citadel_bot_record'
citadel_bot_practice_opponent | sv, rep, release | Default: hero_gigawatt<br>
citadel_bot_practice_teammate | sv, rep, release | Default: hero_kelvin<br>
citadel_bot_record | sv, rep, release | Default: 0<br>Causes bots to mimic your commands as well as record them to be replayed
citadel_bot_shoot | sv, rep, release | Default: 0<br>Forces citadel bots to fire continuously. 1:scope shooting 2:unscope shooting.
citadel_bot_shop | sv, rep, release | Default: 0<br>Forces citadel bots to attempt shopping. 1 = random, 2 = recommended
citadel_bot_takeover_ally_range | sv, rep, release | Default: 30<br>How far from Allies that is acceptable
citadel_bot_takeover_time | sv, rep, release | Default: 30<br>Time for a disconnected player to be taken over by a bot
citadel_bot_test_mode | sv, rep, release | Default: false<br>Set citadel bots to be and in test mode (default idle)
citadel_bot_use_ability | sv, rep, release | Default: 0<br>Causes Bot to Constantly use Ability when its available
citadel_bot_use_ability_once | sv, rep, release | Default: false<br>Set if you only want enemy to use ability once and stop
citadel_bot_use_ability_rate | sv, rep, release | Default: -1<br>Interval in seconds that the bot attempts to use an ability
citadel_bot_use_item_ability | sv, rep, release | Default: 0<br>Causes Bot to Constantly use Ability when its available
citadel_bot_zig_zag | sv, rep, release | Default: 0<br>Forces citadel bots to zig-zag side to side if &gt; 0 or back and forth if &lt; 0
citadel_botmatch_tick_rate_override | sv, cl, rep, release | Default: 32<br>
citadel_bounty_allow_melee_autoclaim | sv, cl, rep, cheat | Default: true<br>Whether or not melees autoclaim orbs.
citadel_bounty_aoe_deny_radius | sv, cl, rep, cheat | Default: 2165.35<br>The radius in which teammates gain a portion denies
citadel_bounty_aoe_radius | sv, cl, rep, cheat | Default: 2165.35<br>The radius in which teammates gain a portion of bounties
citadel_bounty_aoe_radius_autoscore | sv, cl, rep, cheat | Default: 1771.65<br>The radius in which a trooper death is automatically assigned to a nearby player.
citadel_bounty_aoe_radius_neutrals | sv, cl, rep, cheat | Default: 800<br>The radius in which teammates gain a portion of Neutral
citadel_bounty_aoe_radius_non_troopers_non_hero | sv, cl, rep, cheat | Default: 1378<br>The radius in which teammates gain a portion of things besides Nuetrals, Troopers and Players
citadel_bounty_aoe_radius_troopers | sv, cl, rep, cheat | Default: 2165.35<br>The radius in which teammates gain a portion of things besides Neutrals and Players
citadel_bounty_player_assist_window | sv, cl, rep, cheat | Default: 10<br>The recent damage time window to be counted as an assister for player kill
citadel_brawl_hero_roster | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently selected brawl roster heroes
citadel_brawl_hero_roster_high_priority | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently high priority brawl roster heroes
citadel_brawl_hero_roster_preferred | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently preferred brawl roster heroes
citadel_brawl_hero_roster_random | cl, a, release | Default: false<br>Is the brawl hero roster set to random
citadel_bullet_obscured_shot_distance | sv, cl, rep, cheat | Default: 256<br>
citadel_bullet_tracer_recycling_enabled | sv, cl, rep, cheat | Default: 1<br>Recycle bullet tracer effects when &gt;= 1.  Set to 2 to spew when a tracer couldn't be recycled.
citadel_camera_allow_controller_when_controlling_other | cl, cheat | Default: true<br>
citadel_camera_draw_clip_sphere | cl, cheat | Default: false<br>
citadel_camera_height | cl, cheat | Default: 63<br>The look at point of the camera is vertically offset by this distance.
citadel_camera_height_approach_speed | cl, cheat | Default: 800<br>
citadel_camera_height_npc | cl, cheat | Default: 33<br>The look at point of the camera is vertically offset by this distance when viewing NPC units.
citadel_camera_hero_fov | cl, a | Default: 90<br>The field of view angle of the camera when following a hero.
citadel_camera_offset | cl, cheat | Default: -25<br>The look at point of the camera is horizontally offset by this distance.
citadel_camera_pitch_inverted | cl, a | Default: false<br>Set to 1 to have inverted mouse pitch
citadel_camera_sensitivity | cl, a | Default: 1<br>Mouse sensitivity for the camera
citadel_capture_point_enable_fast_capture | sv, cl, rep, cheat | Default: false<br>
citadel_cinematic_intro_duration_npc | sv, cheat | Default: 7.5<br>How long is the cinematic intro applied to npcs (shrine/patron)
citadel_cinematic_intro_duration_player | sv, cheat | Default: 9.5<br>How long is the cinematic intro applied to the player
citadel_cinematic_intro_enabled | sv, cheat | Default: 0<br>-1 = force disabled, 0 = default, 1 = force enabled
citadel_complete_new_player | cl, release | \[flag\] Marks the new player state as complete
citadel_coop_sandbox | sv, cl, rep, release | Default: false<br>
citadel_crate_client_notification_time | sv, cheat | Default: 30<br>
citadel_crate_delivery_base_payoff | sv, cheat | Default: 0<br>
citadel_crate_delivery_overtime_bonus | sv, cheat | Default: 50<br>
citadel_crate_disable_early_spawn |  | 
citadel_crate_early_spawn_delay |  | 
citadel_crate_early_to_trooper_spawn_delay |  | 
citadel_crate_respawn_interval | sv, cheat | Default: 300<br>
citadel_crate_spawn_initial_delay | sv, cheat | Default: 600<br>
citadel_create_test_time_warp | sv, cheat | Create a time warp volume at your feet
citadel_create_unit | sv | \[hero_name \| none\] \[team\] - Creates an unit.  Pass 'my_hero' as hero_name to use your current hero
citadel_crosshair_color_b | cl, a | Default: 255<br>
citadel_crosshair_color_g | cl, a | Default: 255<br>
citadel_crosshair_color_r | cl, a | Default: 255<br>
citadel_crosshair_disable_hero_specific_crosshairs | cl, a | Default: false<br>
citadel_crosshair_dot_opacity | cl, a | Default: 0.7<br>
citadel_crosshair_dot_outline_border | cl, a | Default: 2<br>
citadel_crosshair_dot_outline_gap | cl, a | Default: 0<br>
citadel_crosshair_dot_outline_opacity | cl, a | Default: 0.7<br>
citadel_crosshair_dot_size | cl, a | Default: 4<br>
citadel_crosshair_hit_marker_duration | cl, a | Default: 0.1<br>
citadel_crosshair_outline_color_b | cl, a | Default: 0<br>
citadel_crosshair_outline_color_g | cl, a | Default: 0<br>
citadel_crosshair_outline_color_r | cl, a | Default: 0<br>
citadel_crosshair_pip_gap | cl, a | Default: 4<br>
citadel_crosshair_pip_gap_static | cl, a | Default: false<br>
citadel_crosshair_pip_height | cl, a | Default: 16<br>
citadel_crosshair_pip_opacity | cl, a | Default: 0.5<br>
citadel_crosshair_pip_outline_border | cl, a | Default: 1<br>
citadel_crosshair_pip_outline_gap | cl, a | Default: 0<br>
citadel_crosshair_pip_outline_opacity | cl, a | Default: 0.7<br>
citadel_crosshair_pip_width | cl, a | Default: 2<br>
citadel_damage_offscreen_indicator_disabled | cl, release | Default: true<br>
citadel_death_replay_enabled | sv, cl, rep, release | Default: false<br>
citadel_debug_ent_los | sv, cl, rep, cheat | Default: false<br>Debug : Draw Spheres on Ent Being Los Tested
citadel_debug_trooper_look_target | sv, cheat | Default: false<br>
citadel_debug_zipline_camera_height_add | sv, cl, rep, cheat | Default: 0<br>Add to zipline camera height offset
citadel_debug_zipline_camera_side_add | sv, cl, rep, cheat | Default: 0<br>Add to zipline camera side offset
citadel_decrease_replay_speed | cl, release | Decrease the Replay speed while watching a replay
citadel_demo_highlight_seconds_after | cl, release | Default: 2<br>How many seconds after the highlight event to show when viewing highlights.
citadel_demo_highlight_seconds_before | cl, release | Default: 6<br>How many seconds before the highlight event to show when viewing highlights.
citadel_demo_movie_preload_ticks | cl, release | Default: 2<br>How many ticks of demo playback before we activate movie recording.
citadel_deny_text_max_distance | cl, a | Default: 4000<br>How far away before we stop showing in world deny events.
citadel_dev_test_endgame | cl, cheat, release | Set the Map to test End game content
citadel_dev_test_endgame_server_cmd | sv, cheat, release | Set the Map to test End game content
citadel_disable_duplicate_heroes | sv, cheat, release | Disable usage of Duplicate Heroes
citadel_disable_fast_cooldowns | sv, cheat | Disable fast cooldowns
citadel_disable_fast_stamina | sv, cheat | Disable fast stamina
citadel_disable_no_hero_death | sv, cheat | Make heroes able to die
citadel_disable_unlimited_ammo | sv, cheat | Disable unlimited ammo
citadel_display_new_player_recommendations | cl, release | Default: true<br>Do we want to show the decorations for new player friendly heroes?
citadel_distance_mouse_move_for_minimap_drawing | cl, release | Default: 15<br>
citadel_doorway_debug_draw | sv, cl, rep, cheat | Default: 0<br>
citadel_doorway_glow_other_distance | sv, cl, rep, cheat | Default: 1000<br>
citadel_doorway_infinite_duration | sv, cl, rep, cheat | Default: false<br>
citadel_doorway_portal_forward_offset | sv, cl, rep, cheat | Default: -3<br>
citadel_dps_multiplier | sv, cl, rep, cheat | Default: 1<br>Increase weapon damage for testing
citadel_enable_duplicate_heroes | sv, cheat, release | Enable usage of Duplicate Heroes
citadel_enable_fast_cooldowns | sv, cheat | Enables fast cooldowns
citadel_enable_fast_stamina | sv, cheat | Enables fast stamina
citadel_enable_nearby_capture_point | sv, cheat, release | Enables the first capture point found within 20m
citadel_enable_no_hero_death | sv, cheat | Make heroes unable to die
citadel_enable_unlimited_ammo | sv, cheat | Enables unlimited ammo
citadel_english_hero_names | cl, a | Default: false<br>
citadel_english_mod_names | cl, a | Default: false<br>
citadel_entity_ping_duration | sv, cheat | Default: 6<br>
citadel_exonerate_account | cl, release | &lt;Account ID&gt; Clear recent cheat reports on this account.
citadel_fake_bots_as_pinging_player | sv, cheat | Default: false<br>
citadel_fake_number_of_games_played | cl, release | Default: -1<br>
citadel_fetch_cheat_reports | cl, release | Request accounts recently reported for cheating
citadel_fibonacci_sphere_trace | sv, cheat | Draws the LOS check generated by our fibonacci sphere trace algorithm
citadel_fly_accelerate | sv, cl, rep, cheat | Default: 2<br>
citadel_gamemode_streetbrawl_enabled | sv, cl, rep, release | Default: false<br>
citadel_give_gold | sv, cheat | &lt;gold&gt; Give gold value to all players
citadel_give_player_gold | sv, cheat | &lt;player name&gt; &lt;gold&gt; Gives the specified player gold
citadel_gravity_scaling_experiment | sv, cl, rep, cheat | Default: false<br>Increase gravity for players while they are moving at pedestrian speeds (lateral speeds below 300, up to 500)
citadel_guided_bot_match | sv, cl, rep, release | Default: false<br>
citadel_guided_bot_match_hint_time_mult | cl, release | Default: 0.25<br>How much faster/slower to show hints in guided bot match mode
citadel_guided_bot_t1_boss_ignore_damage_threshold | sv, rep, release | Default: 0<br>
citadel_gun_max_spread_penalty | sv, cl, rep, cheat | Default: 5<br>Max spread penalty you can incur from taking damage
citadel_healthbars_enabled | cl, release | Default: true<br>
citadel_hero_demo_enable_fast_stamina | sv, cl, a, rep, release | Default: false<br>Do we enable fast stamina cooldowns
citadel_hero_demo_enable_unlimited_ammo | sv, cl, a, rep, release | Default: false<br>Do we enable unlimited ammo
citadel_hero_demo_hero_spawn | sv, cl, a, rep, release | Default: hero_inferno<br>Which hero do we spawn when we spawn and enemy or ally hero
citadel_hero_demo_infinite_resources | sv, cl, a, rep, release | Default: true<br>Do we start our hero demo with infinite resources
citadel_hero_demo_no_cooldowns | sv, cl, a, rep, release | Default: false<br>Do we start withough cooldowns when launching the hero demo map
citadel_hero_demo_no_death | sv, cl, a, rep, release | Default: false<br>Do we start withough death when launching the hero demo map
citadel_hero_demo_no_troopers | sv, cl, a, rep, release | Default: false<br>Do we start withough troopers when launching the hero demo map
citadel_hero_demo_persist_convars | sv, cl, a, rep, release | Default: false<br>Do we persist convars between sessions in hero demo
citadel_hero_demo_spawn_items | sv, cl, rep, cheat, release | Default: <br>Items to give a hero post spawn
citadel_hero_demo_unlock_flex_slots | sv, cl, a, rep, release | Default: false<br>Do we start flex slots unlocked
citadel_hero_roster | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently selected roster heroes
citadel_hero_roster_high_priority | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently high priority roster heroes
citadel_hero_roster_preferred | cl, a, release | Default: <br>A comma separated list of hero IDs that hold the currently preferred roster heroes
citadel_hero_roster_random | cl, a, release | Default: false<br>Is the hero roster set to random
citadel_hero_testing_ability1_state | sv, cl, rep, release | Default: 0<br>
citadel_hero_testing_ability2_state | sv, cl, rep, release | Default: 0<br>
citadel_hero_testing_ability3_state | sv, cl, rep, release | Default: 0<br>
citadel_hero_testing_ability4_state | sv, cl, rep, release | Default: 0<br>
citadel_hero_testing_ability_learn_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_ability_purchased_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_ability_upgrade_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_dash_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_dummy_target | sv, release | Default: 55<br>Dummy Target heroID if non-specified
citadel_hero_testing_enabled | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_give_abilities | sv, rep, release | Default: true<br>Grant Abilities on Character Spawn
citadel_hero_testing_guided_sandbox | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_hide_mods | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_infinite_money | sv, cl, rep, release | Default: false<br>Enable infinite money in Hero Testing
citadel_hero_testing_jump_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_mantle_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_mods_purchased_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_money | sv, rep, release | Default: 4000<br>How much money to buffer item purchases in Hero Testing
citadel_hero_testing_movement_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_reload_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_shoot_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_show_intro_modal | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_show_outro_modal | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_wasd_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_zipline_attach_finished | sv, cl, rep, release | Default: false<br>
citadel_hero_testing_zoom_finished | sv, cl, rep, release | Default: false<br>
citadel_hide_replay_hud | cl, release | Default: false<br>
citadel_hideout_accept_request | cl, release | Accept an incoming request in the hideout
citadel_hideout_ball_debug | sv, cheat | Default: 0<br>Show custom collision, ball kick impulses etc.
citadel_hideout_cancel_matchmaking | cl, release | Remove yourself or your party from the matchmaking queue
citadel_hideout_hero_id | cl, a, release | Default: 6<br>
citadel_hideout_intro_version_seen | cl, a, release | Default: 0<br>
citadel_hideout_news | cl, release | Show hideout news
citadel_hideout_reject_request | cl, release | Reject an incoming request in the hideout
citadel_hideout_survey_option | cl, release | &lt;option number&gt; Submit a response to the current survey question
citadel_hideout_survey_skip | cl, release | Skip the current survey question
citadel_hideout_use | cl, release | Interact with a targeted hideout button
citadel_hint_system_disable | cl, release | Default: false<br>Set to disable hints
citadel_hud_exclusive_visible_id | cl, cheat | Default: <br>When set, only show the panel with the corresponding id
citadel_hud_healthbars_use_new | cl, cheat, release | Default: false<br>
citadel_hud_healthbars_use_v2 | cl, cheat, release | Default: false<br>
citadel_hud_visible | cl, release | Default: true<br>Turns on/off rendering the HUD
citadel_increase_replay_speed | cl, release | Increase the Replay speed while watching a replay
citadel_invert_ping_type | cl, a | Default: false<br>Inverts the ping types so single ping would be aggressive and double ping would be passive
citadel_item_draft_enabled | sv, cl, rep, release | Default: 1<br>Use item drafting?  1=only street brawl 2=always
citadel_item_early_gold_duration | sv, cheat | Default: 30<br>
citadel_item_glow_local_dist | cl, cheat | Default: 800<br>
citadel_item_idol_label_offset | cl, cheat | Default: 50<br>
citadel_item_neutral_gold_label_offset | cl, cheat | Default: 6<br>
citadel_item_pickup_fall_tolerance | sv, cheat | Default: 16<br>
citadel_item_pickup_fallrate | sv, cheat | Default: 5<br>
citadel_item_purchases_force_enhanced | sv, cheat | Default: false<br>While true, all items purchased/drafted will be enhanced
citadel_item_rejuvenator_label_offset | cl, cheat | Default: 160<br>
citadel_lane_matchups_mmr_variance | sv, release | Default: 0<br>specifies how much of a gap between MMR's we allow to randomize lane assignment
citadel_lane_swap_available_duration | sv, cl, rep, cheat | Default: 40<br>How long lane swap is available, including pre-match time. Set to 0 to disable.
citadel_last_used_hero_builds | cl, a, release | Default: <br>
citadel_lock_flex_slots | sv, cheat | &lt;team number&gt; - Lock the flex slots for a team (or both teams if you omit the team number)
citadel_loot_table_spew_flattened_table | sv, cl, rep, cheat | Default: false<br>
citadel_loot_table_spew_modifications | sv, cl, rep, cheat | Default: false<br>
citadel_loot_table_test_draft | sv, cheat | Draft from the specified loot table
citadel_loot_table_test_street_brawl_draft_round | sv, cheat | Start the specified street brawl draft round
citadel_mantle_cancelling_allowed | sv, cl, rep, cheat | Default: false<br>Pulling away from the mantle interrupts it, putting you into falling state early.
citadel_mantle_max_height | sv, cl, rep, cheat | Default: 134<br>How high the maximum mantle is
citadel_match_details | cl, release | &lt;MatchID&gt; \[Metadata Salt\] Opens the match details to the specified match
citadel_match_intro_duration_full | sv, cheat | Default: 23<br>How long pre-match is until we start the match in the full version
citadel_match_intro_duration_simple | sv, cheat | Default: 5<br>How long pre-match is until we start the match in the simple version.
citadel_min_accel_speed | sv, cl, rep, cheat | Default: 400<br>How fast we accelerate depends on our move speed - this lower bound ensures it doesn't go below ground friction
citadel_minimap_draw_fow | cl, cheat | Default: false<br>
citadel_minimap_local_player_width | cl, release | Default: 12<br>
citadel_minimap_max_icon_shrink | cl, release | Default: 0.8<br>
citadel_minimap_overlap_scan_distance | cl, release | Default: 12.5<br>
citadel_minimap_player_width | cl, release | Default: 7<br>
citadel_minimap_spectator_fow_team_view | cl, release | Default: 1<br>Which team to view the minimap as when freeflying
citadel_minimap_unit_click_radius | cl, release | Default: 200<br>
citadel_minimap_zip_line_thickness | cl, release | Default: 2<br>
citadel_minimum_fire_rate | sv, cl, rep, cheat | Default: -50<br>Minimum value possible for fire rate
citadel_move_goal_tolerance | sv, cheat | Default: 8<br>Some extra tolerance for considering an NPC moved to a goal; can be reduced as we fix other issues
citadel_new_player_flow_visible | cl, a, release | Default: true<br>Are we still showing the new player instructions
citadel_new_player_progress | cl, a, release | Default: 0<br>Tracks the local settings for the new player progress so they can be synchronized with the GC for client authoratative progress
citadel_new_years_fireworks_test | sv, release | Sets fireworks start time to be N seconds in the future.
citadel_news_entries_seen | cl, a, release | Default: <br>
citadel_no_orbs_on_hero_kill | sv, cl, rep, cheat | Default: true<br>
citadel_no_orbs_on_objective_kill | sv, cl, rep, cheat | Default: true<br>
citadel_npc_allow_climb | sv, rep, cheat | Default: false<br>Allow NPCs to climb.
citadel_npc_allow_jump_down | sv, rep, cheat | Default: true<br>Allow NPCs to follow any drop-down navigation links.
citadel_observer_roaming_speed | cl, a | Default: 600<br>
citadel_one_on_one_match | sv, cl, rep, release | Default: false<br>
citadel_one_on_one_match_starting_gold | sv, cl, rep, cheat, release | Default: 0<br>
citadel_open_ability_vdata_by_name | cl, cheat | Open an ability by name in the VData editor
citadel_open_ability_vdata_by_slot | cl, cheat | Open an ability by slot in the VData editor
citadel_open_hero_sheet | cl, release | Open the current hero character sheet
citadel_open_hero_vdata_by_name | cl, cheat | Open the VData editor to a specified hero
citadel_open_modeldoc_to_model | cl, cheat | Open ModelDoc to the model under the cursor.  Pass any parameter to open your own model
citadel_open_vdata_file_to_node | cl, cheat | Open the VData editor to a specified file and node
citadel_orb_experiment_staticlifetime | sv, rep, cheat | Default: true<br>
citadel_party_invite_in_game | cl, release | Default: true<br>When set, only users in game can be invited
citadel_pause | cl, release | Send a game pause request.
citadel_pause_countdown | sv, cheat | Default: 0<br>Countdown timer to pause after a user has pressed pause
citadel_pause_minimum_time | sv, cheat | Default: 2<br>Disables unpausing for this many seconds after a pause occurs
citadel_per_unit_hotkeys_checked | cl, a | Default: false<br>
citadel_player_attack_enemy_npc_fow_reveal_duration | sv, cheat | Default: 2<br>How long a player is visible to enemy FOW after attacking an enemy trooper or boss
citadel_player_attack_enemy_player_fow_reveal_duration | sv, cheat | Default: 1<br>How long a player is visible to enemy FOW after attacking an enemy player
citadel_player_glow_disabled | cl, cheat, release | Default: false<br>
citadel_player_ground_dash_max_percent | sv, cl, rep, cheat | Default: 2<br>Max ground dash scale
citadel_player_ground_dash_min_percent | sv, cl, rep, cheat | Default: 0.5<br>Min ground dash scale
citadel_player_move_speed_min | sv, cl, rep, cheat | Default: 80<br>Min walk speed
citadel_player_move_speed_scale | sv, cl, rep, cheat | Default: 1<br>Scales how fast players can move
citadel_player_ping_duration | sv, cheat | Default: 6<br>
citadel_player_regen_zone_bonus_base | sv, cl, rep, cheat | Default: 60<br>When standing in a regen zone, how much extra do we regen per second?
citadel_player_regen_zone_bonus_pct | sv, cl, rep, cheat | Default: 6<br>When standing in a regen zone, how much extra do we regen per second based on max health percentage?
citadel_player_regen_zone_stamina_regen | sv, cl, rep, cheat | Default: 150<br>When standing in a regen zone, how much extra do we stamina percentage
citadel_postgame_duration | sv, cheat | Default: 10<br>How long postgame lasts until play of the game
citadel_pregame_wait_duration | sv, cheat | Default: 5<br>How long pre-match is until we start the match
citadel_previous_umuted_audio_level | cl, a | Default: 1<br>
citadel_private_lobby_bot_difficulty | cl, a, release | Default: 0<br>
citadel_private_lobby_cheats_enabled | cl, a, release | Default: false<br>
citadel_private_lobby_duplicate_heroes_enabled | cl, a, release | Default: false<br>
citadel_private_lobby_is_publicly_visible | cl, a, release | Default: false<br>
citadel_private_lobby_randomize_lanes | cl, a, release | Default: false<br>
citadel_private_lobby_server_region | cl, a, release | Default: 0<br>
citadel_purchase_quickbuy | cl, release | Purchase the next quickbuy item
citadel_quickbuy_auto_buy_default | cl, a, user | Default: false<br>Default for whether auto-buy is enabled in normal games.
citadel_quickbuy_enable | cl, a | Default: true<br>If enabled, show quickbuy in the HUD
citadel_rapid_stamina_regen | sv, cl, rep, cheat | Default: false<br>
citadel_recent_comms_recording_window | sv, rep, release | Default: 10<br>
citadel_recent_comms_session_attempt_throttled_count | sv, rep, release | Default: 75<br>
citadel_recent_comms_throttling_limit | sv, rep, release | Default: 10<br>
citadel_recent_comms_throttling_penalty | sv, rep, release | Default: 10<br>
citadel_record_hero_animgraph | sv, cheat | Record the animgraph for a specified hero
citadel_region_override | cl, release | Default: -1<br>Override the region of the client
citadel_render_minimap | cl, release | Render the minimap
citadel_replay_manager_download_chunk_size | cl, a | Default: 1048576<br>
citadel_replay_manager_download_simultaneous_requests | cl, a | Default: 3<br>
citadel_replay_toggle_pause | cl, release | Toggle a replay being paused
citadel_reset_new_player | cl, release | Resets the new player experience back to the initial state
citadel_secondary_language_builds | cl, a | Default: -1<br>
citadel_send_gc_match_info_s | sv, cl, rep, release | Default: 30<br>Determines the rate that we should submit match info up to the GC, 0 disables this functionality
citadel_server_all_players_disconnected_grace_period_s | sv, release | Default: 120<br>How long a server should run after all players have disconnected before notifying that all players have left
citadel_server_max_spectator_slots | sv, release | Default: 3<br>The maximum number of spectator slots we allow. This is so that the GC can restrict this remotely if we need to. -1 disables this limit
citadel_settings_dismissed_new_settings | cl, a | Default: <br>New Settings which have already been dismissed by the user
citadel_settings_seen_new_settings | cl, a | Default: <br>New Settings which have already been seen by the user
citadel_shop_default_tab | cl, a, release | Default: -1<br>
citadel_shop_items_appear_enhanced | cl, cheat | Default: false<br>Makes all of the items in the shop appear enhanced if they can be enhanced
citadel_show_account_ids | cl, release | Default: false<br>When set, account IDs will be shown on player tooltips
citadel_show_active_slot_popup | cl, a, release | Default: false<br>
citadel_show_all_purchase_toasts | cl, a | Default: false<br>If enabled, show purchase toasts for all item transactions, not just ones in your quickbuy queue
citadel_show_average_rating_on_postgame | cl, a, release | Default: false<br>Show the rating average rating of a team in the post game.
citadel_show_bullet_lag_compensation | sv, cl, rep, cheat | Default: 0<br>if &gt; 0.0, show lag compensated hitboxes (value is seconds) whenever a bullet is lag compensated and hits something.
citadel_show_global_leaderboard | cl, release | Default: false<br>Show Global Leaderboards
citadel_show_hero_lab_heroes | cl, a | Default: false<br>Show Hero Labs Heroes in hero grid
citadel_show_npe_modal | cl, a, release | Default: true<br>Show the NPE modal when navigating to the roster select.
citadel_show_page_reload_button | cl, a | Default: true<br>Show beta db controls in the upper left corner
citadel_show_rating_notification_on_change | cl, a, release | Default: false<br>Show the rating notification on the post game if your rating changed that game.
citadel_show_telemetry_settings | cl, release | Default: false<br>Show HUD Telemetry Settings.
citadel_snowball_level_override | sv, cheat, release | Default: -1<br>Change the snowball level
citadel_solo_bot_match | sv, cl, rep, release | Default: false<br>
citadel_spawn_all_heroes_in_a_line | sv, cheat | Spawn all of the heroes as bots in a line in front of you
citadel_spawn_escort | sv, cheat, release | Spawns the escort with an optional delay
citadel_spawn_nearby_neutrals | sv, cheat, release | Spawns any neutral camps within 800 units (~20m)
citadel_spawn_practice_bots | sv, release | Default: false<br>
citadel_spawn_practice_bots_count | sv, release | Default: 1<br>
citadel_spawn_urn | sv, cheat | Spawn an urn for testing
citadel_spectator_voice_mode | cl, user | Default: true<br>Spectator voice transmit mode: 0 spectators and players, 1 spectators only
citadel_spectator_voice_mode_toggle | cl, release | Toggle the value of citadel_spectator_voice_mode
citadel_streaming_mode_enabled | cl, a, release | Default: false<br>Enable to alter various game UI elements
citadel_stuck_camera_trace_extra_length | sv, cl, rep, cheat | Default: 100<br>
citadel_stuck_normal_find_trace_fallback_elevation | sv, cl, rep, cheat | Default: 24<br>
citadel_teleporter_enabled_time | sv, cl, rep, cheat | Default: 1<br>
citadel_test_survey_popup | cl, cheat | Tests bringing up the survey popup
citadel_tether_pull_speed | sv, cl, rep, cheat | Default: 200<br>
citadel_tether_pull_speed_scale_per_meter | sv, cl, rep, cheat | Default: 120<br>
citadel_tightcamera_alternative | cl, a | Default: 1.3<br>Tight-camera test mode alternative.
citadel_time_after_damage_to_show_hints | cl, release | Default: 10<br>Time after the local player has taken damage from another player before we show hints again.
citadel_toggle_mute | cl, release | Toggles muting/unmuting the audio.
citadel_track_player_vs_player_accuracy | sv, cl, rep, cheat | Default: true<br>
citadel_trooper_glow_disabled | cl, release | Default: false<br>
citadel_trooper_instant_gold_as_dropped_orbs | sv, release | Default: 2<br>0=instant gold 1=orbs in experimental only 2=orbs always
citadel_trooper_medic_drops_health_pack | sv, release | Default: true<br>
citadel_trooper_medics_use_heal_ability | sv, release | Default: false<br>
citadel_trooper_spawn_interval |  | 
citadel_ui_allow_feature_bot_test | cl, release | Default: true<br>When true, we can feature bot test matches
citadel_ui_watch_active_game_refresh_s | cl, release | Default: 5<br>The number of seconds to wait between refreshes of the active matches while on the watch page
citadel_unit_status_enabled | cl, cheat, release | Default: true<br>
citadel_unit_status_hide_names | cl, cheat, release | Default: false<br>
citadel_unit_status_old_hide_names | cl, cheat, release | Default: false<br>
citadel_unit_status_single_bar_mode | cl, cheat | Default: false<br>Allow only a single health bar, no stacking.
citadel_unit_status_use_new | cl, release | Default: false<br>
citadel_unlock_flex_slots | sv, cheat | &lt;team number&gt; - Unlock the flex slots for a team (or both teams if you omit the team number)
citadel_unpause_countdown | sv, cheat | Default: 3<br>Countdown duration to the unpause after a user unpauses
citadel_update_gc_connection_check_count | sv, cheat | Default: 50<br>How many tries we check if the GC is still connected before terminating due to no response
citadel_update_gc_connection_check_time | sv, cheat | Default: 1200<br>How often the server should check the GC is still connected (in seconds)
citadel_update_gc_connection_check_time_variance | sv, cheat | Default: 60<br>How much variance to allow the GC check time to avoid swamping the GC (in seconds)
citadel_upload_replay_enabled | sv, release | Default: true<br>Controls if replay uploading is enabled. Mainly used as a kill switch if something goes wrong
citadel_use_contextual_ping_wheel_option | cl, a | Default: true<br>
citadel_use_shop_component_groupings | cl, a | Default: false<br>Use new component Grouping
citadel_use_ui_keybindings | cl, a, release | Default: true<br>Use UI key bindings otherwise use engine keybindings.
citadel_video_preset | cl, a | Default: 3<br>Rendering performance level.
citadel_viewed_book_prototype | cl, a, release | Default: false<br>Track if they have opened up the book prototype or not yet
citadel_viewpunch_damping | sv, cl, rep, cheat | Default: 9<br>Bigger number makes the response more damped, smaller is less damped
citadel_viewpunch_spring_constant | sv, cl, rep, cheat | Default: 15<br>Bigger number increases the speed at which the view corrects
citadel_visualize_tethers | sv, cl, rep, cheat | Default: false<br>
citadel_waiting_for_map_load_min_duration | sv, cheat | Default: 0<br>Force a certain duration in the waiting for map to load state
citadel_wall_detection_debug | sv, cl, rep, cheat | Default: 0<br> 1: Show all wall normal planes detected
citadel_wall_detection_skin | sv, cl, rep, cheat | Default: 8<br>Maximum distance to a wall in order to wall jump.
citadel_wall_slide_terminal_velocity | sv, cl, rep, cheat | Default: 600<br>While wall gripping, gravity will be cancelled out at this speed down the wall
citadel_weapon_damage_multiplier | sv, cl, rep, cheat | Default: 1<br>Multiply the damage on guns
citadel_weapon_damage_multiplier_team_filter | sv, cl, rep, cheat | Default: -1<br>Filter which team gets a multiplier on their gun damage. -1 = no filter (all teams get multiplier), 2 = amber, 3 = sapphire, etc
citadel_weapon_normalize_recoil_with_firerate | sv, cl, rep, cheat | Default: true<br>Keep recoil constant even with fire rate changes.
citadel_weapon_zoom_style | sv, cl, rep, cheat | Default: 1<br>0: Original Linear Interpolation. 1: Smooth Approach
citadel_zipline_show_enemy_boosting | sv, cl, rep, cheat | Default: 1<br>0 = no, 1 = yes, 2 = preview effect
cl_audio_debug_bullet_material | cl, cheat | Default: false<br>Visualize bullet material info.
cl_audio_debug_pawn_surface_data | cl, cheat | Default: false<br>Visualize pawn surface data.
cl_audio_display_soundstack_debug_base_3d | cl, cheat | Default: false<br>Displays citadel_base_3d sound stack debug.
cl_audio_display_soundstack_debug_dialog | cl, cheat | Default: false<br>Displays citadel_dialog sound stack debug.
cl_audio_log_participant_start_messages | cl, cheat | Default: false<br>Prints when a participant sound message was sent.
cl_auto_cursor_scale | a | Default: true<br>Automatic cursor size scaling.
cl_axis | cl, cheat | Draw an axis<br>	Arguments:  x y z pitch yaw roll &lt;lifetime = 10.0&gt; &lt;r g b a&gt;<br>
cl_box | cl, cheat | Draw a bbox<br>	Arguments:  minx miny miny maxx maxy maxz &lt;lifetime = 10.0&gt; &lt;r g b a&gt;<br>
cl_buffer_incoming_net_messages | release | Default: true<br>
cl_bullet_travel_debug_path | cl, cheat | Default: 0<br>Debug: visualization time for lazily calculated bullet paths (0 = disable)
cl_bullet_travel_debug_trace | cl, cheat | Default: 0<br>Debug: visualization time for active bullet traces (0 = disable)
cl_change_callback_limit | cl, release | Default: 0.2<br>change callback msec warning limit
cl_checkdeclareclasses | cheat | Check game code serializers
cl_citadel_ability_alt_cast_hold_time | cl, a, user | Default: 0.15<br>
cl_citadel_ability_alt_cast_instant_cast_double_tap_timeout | cl, a, user | Default: 0.2<br>
cl_citadel_ability_alt_cast_mode | cl, a, user | Default: 2<br>
cl_citadel_bebop_beam_draw_points | cl, cheat | Default: false<br>
cl_citadel_cancel_with_ability_key_enabled | cl, a, user | Default: false<br>
cl_citadel_items_quickcast_mode | cl, a, user | Default: 0<br>
cl_citadel_player_voting_poster_current_hero_id | sv, cl, a, user | Default: 0<br>Hero ID to spray
cl_citadel_quickcast_ability1 | cl, a, user | Default: 0<br>
cl_citadel_quickcast_ability2 | cl, a, user | Default: 0<br>
cl_citadel_quickcast_ability3 | cl, a, user | Default: 0<br>
cl_citadel_quickcast_ability4 | cl, a, user | Default: 0<br>
cl_citadel_record_hero_animgraph | cl, cheat | Record the animgraph for a specified hero
cl_citadel_zoom_is_toggle | cl, a, user | Default: false<br>
cl_clock_correction | cheat | Default: true<br>Enable/disable clock correction on the client.
cl_clock_recvmargin_spew_interval | release | Default: 0<br>
cl_connectionretrytime_p2p | release | Default: 20<br>Number of seconds over which to spread retry attempts for P2P.
cl_cq_min_queue | user | Default: 0<br>Used by the client to inform the server of their desired queue length.  Derived from cl_tickpacket_recvmargin_desired and cl_tickpacket_desired_queuelength
cl_cursor_scale | a | Default: 1<br>Cursor size scaling factor.
cl_debug_overlays_broadcast | release | Default: false<br>Render debug overlays from server.
cl_debugoverlay_cycle_domain | cl, cheat | Toggles visibility of the debug overlay system.
cl_debugoverlay_cycle_state | cl, cheat | Toggles visibility of the debug overlay system.
cl_debugoverlay_dashboard | cl, cheat | Makes the debug overlay dashboard visible.
cl_debugoverlay_hide_imgui | cl, cheat | Hides the overlay.
cl_debugoverlay_toggle | cl, cheat | Toggles visibility of the debug overlay system.
cl_disable_ragdolls | cl, cheat | Default: false<br>
cl_display_game_events | cl, cheat | Default: false<br>
cl_draw_simulating_entities | cl, cheat | Default: false<br>
cl_drawcross | cl, cheat | Draws a cross at the given location<br>	Arguments: x y z
cl_drawhud | cl, cheat | Default: true<br>Enable the rendering of the hud
cl_drawline | cl, cheat | Draws line between two 3D Points.<br>	Green if no collision<br>	Red is collides with something<br>	Arguments: x1 y1 z1 x2 y2 z2
cl_dumpentity | cl, cheat | Dumps info about an entity
cl_ent_absbox | cl, cheat | Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_actornames | cl, cheat | Displays the entity name for all entities that have ShouldDisplayInActorNames true in code
cl_ent_animgraph2_open_graph | cl, cheat | Opens the graph and starts live debugging the AG2 graph for a given entity<br>	Arguments: entityName<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_animgraph2_record | cl, cheat | Starts live debugging & recording the AG2 graph for a given entity<br>	Arguments: entityName<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_animgraph_debug | cl, cheat | Displays debug draws about the given entity(ies) animgraph<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_animgraph_record | cl, cheat | Toggles recording of animgraph replay of the given entity(s)<br>	Arguments: entityName automaticallyOpenInAnimgraphEditor<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_attachment_filter_substrings | cl, cheat | Default: <br>If an attachment's name has any of the given substrings in it, it will be displayed. Substrings can be delimited by the ',' or '\|' character.
cl_ent_attachments | cl, cheat | Displays the attachment points on an entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_bbox | cl, cheat | Displays the movement bounding box for the given entity(ies) in orange.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_call | cl, cheat | ent_call &lt;funcname&gt; &lt;option:entname&gt; calls function on current look target or filtername, checks on ent, then root, then mode, then map scope
cl_ent_clear_debug_overlays | cl, cheat | Clears all debug overlays
cl_ent_find | cl, cheat | Find and list all entities with classnames or targetnames that contain the specified substrings.<br>Format: find_ent &lt;substring&gt;<br>
cl_ent_find_index | cl, cheat | Display data for entity matching specified index.<br>Format: find_ent_index &lt;index&gt;<br>
cl_ent_grab | cl, cheat | grabs the object in front of the player. Options: -loose -multiple -toggle
cl_ent_hierarchy | cl, cheat | Prints the entity hierarchy tree rooted at the specified ent(s)
cl_ent_hitbox | cl, cheat | Displays the hitboxes for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_joint_filter_substrings | cl, cheat | Default: <br>If a joint's name has any of the given substrings in it, it will be displayed. Substrings can be delimited by the ',' or '\|' character.
cl_ent_joint_lines | cl, cheat | Default: true<br>Draw a line between a rendered joint and its parent.
cl_ent_joint_names | cl, cheat | Default: true<br>Draw the name of a rendered joint.
cl_ent_joints | cl, cheat | Displays the joint names + axes an entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_messages | cl, cheat | Toggles input/output message display for the selected entity(ies).  The name of the entity will be displayed as well as any messages that it sends or receives.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_name | cl, cheat | Displays the entity name
cl_ent_picker | cl, cheat | Toggles 'picker' mode.  When picker is on, the bounding box, pivot and debugging text is displayed for whatever entity the player is looking at.<br>	Arguments:	full - enables all debug information
cl_ent_pivot | cl, cheat | Displays the pivot for the given entity(ies).<br>	(y=up=green, z=forward=blue, x=left=red). <br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_pivot_size | cl, a, cheat | Default: 20<br>
cl_ent_remove | cl, cheat | Removes the given entity(s)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_remove_all | cl, cheat | Removes all entities of the specified type<br>	Arguments:   	{entity_name} / {class_name}
cl_ent_scale | cl, cheat | Scales entities.	Arguments: &lt;scale factor&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
cl_ent_scenehierarchy | cl, cheat | Prints the entity scenenode hierarchy tree rooted at the specified ent(s)
cl_ent_script_dump | cl, cheat | Dumps the names and values of this entity's script scope to the console<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_select | cl, cheat | Select or deselects the given entities(s) for later manipulation<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_setang | cl, cheat | Set entity angles
cl_ent_setname | cl, cheat | Sets the targetname of the given entity(s)<br>	Arguments:   	&lt;new entity name&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
cl_ent_setpos | cl, cheat | Move entity to position
cl_ent_show_contexts | cl, cheat | Default: false<br>Show entity contexts in ent_text display
cl_ent_show_damage | cl, cheat | Sets damage display mode.  When on, you will see the amount of damage dealt over the target's head.
cl_ent_showonlyattachment | cl, cheat | Default: <br>
cl_ent_showonlyhitbox | cl, cheat | Default: -1<br>
cl_ent_skeleton | cl, cheat | Displays the skeleton for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text | cl, cheat | Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text256 | cl, cheat | Displays text debugging information about the given entity(ies) \[within 256 units of the player\] on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text_clear | cl, cheat | Hide text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text_filter | cl, cheat | Set which ent_text filters you want:
cl_ent_text_flags_active | cl, a, cheat | Default: -1<br>
cl_ent_text_no_name_really_i_mean_it | cl, cheat | Default: false<br>
cl_ent_text_radius | cl, cheat | Displays text debugging information about the given entity(ies) \[near the player\] on top of the entity (See Overlay Text)<br>	2 Arguments:   	&lt;Radius&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
cl_ent_text_sticky_add | cl, cheat | Adds to list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text_sticky_clear | cl, cheat | Clears the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text_sticky_dump | cl, cheat | Spews the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_text_sticky_remove | cl, cheat | Removes from the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_ungrab | cl, cheat | un-grabs all objects
cl_ent_vcollide_wireframe | cl, cheat | Displays the interpolated vcollide wireframe pm am entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_viewoffset | cl, cheat | Displays the eye position for the given entity(ies) in red.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_ent_visibility_traces | cl, cheat | Displays visibility traces for the given entity<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_error_report_time | cl, release | Default: 0<br>Minimum time in seconds that must elapse before printing prediction error summary. 0 to disable.
cl_extrapolate | cl, cheat | Default: true<br>Enable/disable extrapolation if interpolation history runs out.
cl_extrapolate_amount | cl, cheat | Default: 0.25<br>Set how many seconds the client will extrapolate entities for.
cl_eye_occlusion_debug | cl, cheat | Default: false<br>
cl_flushentitypacket | cheat | Default: 0<br>For debugging. Force the engine to flush an entity packet.
cl_frametime_summary_report_detailed | cl, release | Default: true<br>When a perf report is dumped at the end of the session, should it be detailed?
cl_fullupdate | cheat | Force uncompressed update
cl_glow_brightness | cl, cheat | Default: 1<br>Brightness of player halos
cl_glow_item_far_b | cl, release | Default: 1<br>
cl_glow_item_far_g | cl, release | Default: 0.4<br>
cl_glow_item_far_r | cl, release | Default: 0.3<br>
cl_graphics_driver_warning_ignore_timestamp | cl, a, release | Default: 0<br>
cl_groups | cl, cheat | Show status of all spawn groups.
cl_hold_game_events_force_delay_ticks | cl, cheat | Default: 0<br>Debugging convar to force late dispatch of game events.
cl_hold_game_events_until_server_tick | cl, cheat | Default: true<br>Holds game events until client has received the tick the event was fired on.
cl_hud_telemetry_frametime_poor | cl, a, release | Default: 100<br>Frame time greater than this is considered 'poor'.
cl_hud_telemetry_frametime_show | cl, a, release | Default: 1<br>Show frame time (FPS) in the HUD.  0=never, 1=only if poor, 2=always
cl_hud_telemetry_net_detailed | cl, a, release | Default: 0<br>Show breakdown network misdelivery (loss, late delivery, and peak jitter).  0=never, 1=only in poor network conditions, 2=always
cl_hud_telemetry_net_misdelivery_poor | cl, a, release | Default: 5<br>Packet delivery anomaly rate (0..100) higher than this is considered 'poor'.
cl_hud_telemetry_net_misdelivery_show | cl, a, release | Default: 1<br>Show percentage of user commands & server snapshots that are missed due to network conditions.  0=never, 1=only in poor conditions, 2=always
cl_hud_telemetry_net_quality_graph_show | cl, a, release | Default: 0<br>Show packet jitter and netframe loss/reordering in the HUD.  0=never, 1=only in poor conditions, 2=always
cl_hud_telemetry_ping_poor | cl, a, release | Default: 100<br>Ping higher than this (ms) is considered 'poor'.
cl_hud_telemetry_ping_show | cl, a, release | Default: 1<br>Show ping in the HUD.  0=never, 1=only in poor conditions, 2=always
cl_hud_telemetry_serverrecvmargin_graph_show | cl, a, release | Default: 0<br>Show graph of the server recv margin in the HUD.  (How early/late user commands are arriving at the server before they are executed.)   0=never, 1=only when there are command queue problems, 2=always
cl_ignorepackets | cheat | Default: false<br>Force client to ignore packets (for debugging).
cl_imgui_debug_entity | cl, cheat | Shows the entity browser, focused on the entity you specify.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cl_imgui_set_selection | cl, cheat | Sets ImGui selection
cl_imgui_set_status_text | cl, cheat | Sets ImGui header status text
cl_input_enable_raw_keyboard | release | Default: false<br>Enable raw keyboard input
cl_interp | cl, release | Read the effective client simulation interpolation amount in terms of time.
cl_interp_hermite | cl, cheat | Default: true<br>Set to zero do disable hermite interpolation.
cl_interp_ratio | cl, user | Default: 0<br>Sets the client simulation interpolation amount, in terms of server updates (final amount is cl_interp_ratio / cl_updaterate).
cl_interpolate_report | cl, a | Default: false<br>Enable to show interpolation profile timing<br>
cl_jitter_bad_threshold_up | user | Default: 20<br>When upstream packet jitter in a frame exceeds this threshold (ms), the frame is considered to have 'irregular delivery'.  This is a derived value and should not be modified manually
cl_joystick_enabled | a | Default: false<br>Enable joystick input
cl_lagcompensation | cl, user | Default: true<br>Perform server side lag compensation of weapon firing events.
cl_latch_report | cl, a | Default: false<br>Enable to output stats about latching
cl_leveloverview | cl, cheat | Default: 0<br>
cl_lightquery_debug | cl, cheat | Default: false<br>
cl_lock_camera | cl, cheat | Default: false<br>
cl_max_particle_pvs_aabb_edge_length | release | Default: 100<br>
cl_meep_mop_volume_trigger_max_count | cl, cheat | Default: 10<br>Number of triggers before meemop reaches full volume
cl_modifier_dump | cl, cheat | Display all modifiers for the unit: &lt;entityindex/name&gt;
cl_modifier_dump_list | cl, cheat | Dumps all modifiers that exist in the game
cl_modifier_dump_visible | cl, cheat | Print out non-hidden modifiers.
cl_modifier_spew_states | cl, cheat | Call to have the client spew their unit states affecting them,
cl_modifier_stringtable_dump | cl, cheat | Displays the contents of the modifier string table
cl_net_printsummary | norecord, release | Print a summary report of Source2 engine networking statistics.  (Ticks, netchan messages, etc.)
cl_network_quality2 | cl, a | Default: -1<br>
cl_particle_retire_cost | cheat | Default: 0<br>
cl_particle_simulate | cheat | Default: true<br>Enables/Disables Particle Simulation
cl_pclass | cl, cheat | Default: <br>Dump entity by prediction classname.
cl_pdump | cl, cheat | Default: -1<br>Dump info about this entity to screen.
cl_phys_debug_callback_entities | cl, cheat | Default: false<br>Print all entities that get touch callbacks. Each entity is printed only once.
cl_phys_enabled | cl, cheat | Default: true<br>Enable all physics simulation
cl_phys_sleep_enable | cl, cheat | Default: true<br>Enable sleeping for dynamic physics bodies.
cl_phys_sound_disable_impact_sounds_under_hard_threshold | cl, cheat | Default: false<br>if true, impact sounds wont play if no soft impact sound is present and the impact is below the hard velocity threshold.
cl_phys_stop_at_collision | cl, cheat | Default: <br>
cl_pitchdown | cl, cheat | Default: 89<br>
cl_pitchup | cl, cheat | Default: 89<br>
cl_poll_network_early | release | Default: false<br>Enable polling for network messages every frame, instead of every tick
cl_pred_always_latch | cl, release | Default: false<br>
cl_pred_print_every_cmd | cl, release | Default: false<br>Print something every time we predict a command
cl_predict | cl, user, cheat | Default: true<br>Perform client side prediction.
cl_prediction_savedata_postentitypacketreceived | cl, release | Default: false<br>Experimental optimization.  If you are reading this in 2026, please delete this convar.
cl_prop_debug | cl, cheat | Toggle prop debug mode. If on, props will show colorcoded bounding boxes. Red means ignore all damage. White means respond physically to damage but never break. Green maps health in the range of 100 down to 1.
cl_querycache_stats | cl, cheat | Display status of the query cache (client only)
cl_ragdoll_limit | cl, a | Default: 20<br>Maximum number of ragdolls to show (-1 disables limit)
cl_ragdoll_lru_debug | cl, rep, cheat | Default: false<br>
cl_removedecals | cl, cheat | Remove the decals from the entity under the crosshair.
cl_resend | release | Default: 0.5<br>Delay in seconds before the client will resend the 'connect' attempt
cl_rr_dump_rules | cl, cheat | Print all response rules
cl_rr_reloadresponsesystems | cl, cheat | Reload all response system scripts.
cl_save_animgraph_recording | cl, cheat | Saves all active animgraph recordings to disk<br>	Arguments: automaticallyOpenInAnimgraphEditor
cl_scale_function_dump | cl, cheat | Print out all scale functions.
cl_script_add_debug_filter | cl, cheat | Add a filter to the game debug overlay
cl_script_add_watch | cl, cheat | Add a watch to the game debug overlay
cl_script_add_watch_pattern | cl, cheat | Add a watch to the game debug overlay
cl_script_attach_debugger | cl, cheat | Connect the vscript VM to the script debugger
cl_script_clear_watches | cl, cheat | Clear all watches from the game debug overlay
cl_script_debug | cl, cheat | Toggle the in-game script debug features
cl_script_dump_all | cl, cheat | Dump the state of the VM to the console
cl_script_find | cl, cheat | Find a key in the VM
cl_script_help | cl, cheat | Output help for script functions
cl_script_reload | cl, cheat | Reload scripts
cl_script_reload_code | cl, cheat | Execute a vscript file, replacing existing functions with the functions in the run script
cl_script_reload_entity_code | cl, cheat | Execute all of this entity's VScripts, replacing existing functions with the functions in the run scripts
cl_script_remove_debug_filter | cl, cheat | Remove a filter from the game debug overlay
cl_script_remove_watch | cl, cheat | Remove a watch from the game debug overlay
cl_script_remove_watch_pattern | cl, cheat | Remove a watch from the game debug overlay
cl_script_resurrect_unreachable | cl, cheat | Use the garbage collector to track down reference cycles
cl_script_trace_disable | cl, cheat | Turn off a particular trace output by file or function name
cl_script_trace_disable_all | cl, cheat | Turn off all trace output
cl_script_trace_disable_key | cl, cheat | Turn off a particular trace output by table/instance
cl_script_trace_enable | cl, cheat | Turn on a particular trace output by file or function name
cl_script_trace_enable_all | cl, cheat | Turn on all trace output
cl_script_trace_enable_key | cl, cheat | Turn on a particular trace output by table/instance
cl_showents | cl, cheat | Dump entity list to console.
cl_showerror | cl, release | Default: 0<br>Show prediction errors, 2 for above plus detailed field deltas, 3 to filter out serverside known prediction errors, -entindex for specific entity.
cl_showfps | cl, release | Default: 0<br>Draw fps meter at top of screen (1 = fps, 2 = smooth fps, 3 = server MS, 4 = Show FPS and Log to file )
cl_showframenumber | cl, release | Default: false<br>Show current framenumber
cl_showmem | cl, release | Default: 0<br>Draw approximate memory use at top of screen
cl_showpos | cl, cheat, release | Default: 0<br>Draw current position at top of screen
cl_showtick | cl, release | Default: 0<br>Show current tick/time values.  Bitmask:  1='render time'  2='GameTime'   4=time of predicted entities  8=offset of predicted entities    (-1 means 'everything')
cl_skel_constraints_enable | rep, cheat | Default: true<br>
cl_skeleton_instance_smear_boneflags | cl, cheat | Default: false<br>Smear boneflags across the model.  Costs computation, but tests to make sure your bone flags are consistent.
cl_smooth_draw_debug | cl, cheat | Default: false<br>
cl_smooth_root_catchup_factor | cl, cheat | Default: 0.21<br>
cl_smooth_root_max_accel | cl, cheat | Default: 1000<br>
cl_smooth_root_origin_coeff | cl, cheat | Default: 100<br>
cl_smooth_root_timehorizon | cl, cheat | Default: 0.125<br>
cl_smooth_root_velocity_coeff | cl, cheat | Default: 20<br>
cl_smooth_targetspeed | cl, release | Default: 150<br>
cl_snd_new_visualize | cl, cheat | Default: false<br>Displays soundevent name played at it's 3d position
cl_soundscape_flush | cl, cheat, server_can_execute | Flushes the client side soundscapes
cl_spewserializers | cheat | Spew serializers
cl_test_list_entities | cl, cheat | test-list entities
cl_tickpacket_desired_queuelength | user | Default: 0<br>This value, multiplied by the tick interval, is added to cl_tickpacket_recvmargin_desired to obtain the effective desired recv margin.
cl_tickpacket_recvmargin_spew_interval | release | Default: 0<br>
cl_ticks_net_print_threshold | release | Default: 2<br>Print a message if network issues cause problems with server snapshots of user commands not being available when needed, if the percentage (0...100) exceeds this value.  A value of 0 will cause the message to always print each time it is calculated
cl_ticks_warning_level | release | Default: 0<br>Print a message about problems with ticks and interpolation.  0=never, 1=warnings, 2=all, even if hidden by interpolation
cl_ticktiming | norecord, release | {print\|&lt;interval&gt;} \[summary\|detail\]  Print timing stats now, or set report interval
cl_timeout | a | Default: 30<br>After this many seconds without receiving a packet from the server, the client will disconnect itself
cl_trueview_show_status | cl, release | Default: 2<br>0=Never; 1=Only if there is a problem; 2=always
cl_updaterate | cl, a, user | Default: 20<br>Number of packets per second of updates you are requesting from the server
cl_usercmd_max_per_movemsg | release | Default: 4<br>max number of CUserCmds to send in one client move message
cl_voice_transmit_lobby | cl, a, release | Default: false<br>
clear | norecord, release | Clear console output.
clearall | norecord, release | Clear console output from all views.
cli_ent_attachments | cl, cheat | Displays the interpolated attachment points on an entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cli_ent_hitbox | cl, cheat | Displays the skeleton for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cli_ent_pivot | cl, cheat | Displays the interpolated pivot for the given entity(ies).<br>	(y=up=green, z=forward=blue, x=left=red). <br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cli_ent_skeleton | cl, cheat | Displays the skeleton for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
cli_ent_vcollide_wireframe | cl, cheat | Displays the interpolated vcollide wireframe pm am entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
clientport | release | Default: 0<br>If non-zero, client binds port to specific address.  Usually you should leave this blank to use a different random system-assigned port for each connection.
closecaption | cl, a, user | Default: false<br>Enable close captioning.
collect_entity_model_name | sv, cheat | Collect model names of the entities you're pointing at
commentary | sv, a | Default: false<br>Desired commentary mode state.
commentary_finishnode | sv | 
con_enable | a, per_user | Default: false<br>Allows the console to be activated.
condump | release | dump the text currently in the console to condumpXX.log
connect | release | Connect to a remote server.
connect_hltv | release | Connect to a remote HLTV server.
consoletool | norecord, release | Open a VConsole subtool.
cq_buffer_bloat_msecs_max | rep, release | Default: 120<br>Server will not allow the client to buffer up more than N ms of commands.
cq_logging | sv, release | Default: false<br>command queue logging of events.
cq_logging_interval | sv, release | Default: 0<br>command queue logging per player stats every N seconds, 0 to disable.
cq_max_starved_substitute_commands | sv, release | Default: 4<br>Server will stop generating substitute commands if client hasn't sent one, after N in a row
cq_print_every_command | sv, release | Default: false<br>print every command as we execute it
crash | cheat | Crash the client. Optional parameter -- type of crash:<br> 0: read from NULL<br> 1: write to NULL<br> 2: force an Assert<br> 3: infinite loop<br> 4: stack buffer overrun<br> 5: multiple asserts across multiple threads. Optional number of threads (default 5)<br> 6: looping memory leak until we're out of memory. Optional allocation size in bytes (default 1048576/1MB)
crash_error | cheat | Cause the engine to crash by Plat_FatalError on main thread (Debug!!)
crash_error_job | cheat | Cause the engine to crash by Plat_FatalError on job thread (Debug!!)
crash_error_thread | cheat | Cause the engine to crash by Plat_FatalError on non-main thread (Debug!!)
crash_job | cheat | Cause the engine to crash in a job thread (Debug!!)
crash_thread | cheat | Cause the engine to crash in a brand new non-main thread (Debug!!)
create_radius_damage | sv, cheat | Causes radius damage where you're looking, at the passed in radius.
csm_bias_override_0 | cheat | Default: 1<br>
csm_bias_override_1 | cheat | Default: 1<br>
csm_bias_override_2 | cheat | Default: 1<br>
csm_bias_override_3 | cheat | Default: 1<br>
csm_cascade0_override_dist | cheat | Default: -1<br>
csm_cascade1_override_dist | cheat | Default: -1<br>
csm_cascade2_override_dist | cheat | Default: -1<br>
csm_cascade3_override_dist | cheat | Default: -1<br>
csm_cascade_viewdir_shadow_bias_scale | cheat | Default: 2<br>
csm_max_dist_between_caster_and_receiver | cheat | Default: 15000<br>default pushback
csm_max_visible_dist | cheat | Default: 7500<br>
csm_res_override_0 | cheat | Default: 0<br>
csm_res_override_1 | cheat | Default: 0<br>
csm_res_override_2 | cheat | Default: 0<br>
csm_res_override_3 | cheat | Default: 0<br>
csm_shadow_worldview_align_x_to_u | cheat | Default: false<br>
csm_shadow_worldview_shear_align_z_to_v | cheat | Default: false<br>
csm_split_log_scalar | cheat | Default: 0.85<br>
csm_sst_max_visible_dist | cheat | Default: 2000<br>
csm_sst_pushback_distance | cheat | Default: 1500<br>default pushback
csm_sst_shadow_focus_region_maxz | cheat | Default: 2000<br>
csm_sst_shadow_focus_region_minz | cheat | Default: -2000<br>
csm_viewdir_shadow_bias | cheat | Default: 0<br>
csm_viewmodel_farz | cheat | Default: 30<br>
csm_viewmodel_max_shadow_dist | cheat | Default: 21<br>
csm_viewmodel_max_visible_dist | cheat | Default: 1000<br>
csm_viewmodel_nearz | cheat | Default: 0.5<br>
cvar_unhide |  | 
cvarlist | release | Show the list of convars/concommands.
cvarlist_md |  | List all convars/concmds in Markdown format. Format: \[hidden\]
cyclevar | norecord, release | Cycle through specified convar values.
deadlock_chat_mode | cl, a, release | Default: 2<br>Default communication preference for players
deadlock_disable_post_match_survey | cl, a | Default: false<br>Disable the early post match survey
deadlock_early_development_warning_disabled | cl, a | Default: false<br>Disable the early dev build message
deadlock_hero_debuts_seen | cl, a, release | Default: <br>
deadlock_mm_preference | cl, a, release | Default: 1<br>What style of player do we want to try and match with in matchmaking
debug_destructible_parts_enabled | sv, cl, rep, cheat | Default: true<br>Toggle enabling/disabling the destructible parts system for debug.
debug_error_model | sv, cl, rep, cheat | Default: false<br>
debug_radial_damage | sv, cl, rep, cheat | Default: false<br>
debug_takedamage_summaries | sv, cheat | Default: false<br>
debug_visibility_monitor | sv, cheat | Default: 0<br>
debugoverlay_cycle_domain | sv, cheat | Toggles visibility of the debug overlay system.
debugoverlay_cycle_state | sv, cheat | Toggles visibility of the debug overlay system.
debugoverlay_dashboard | sv, cheat | Makes the debug overlay dashboard visible.
debugoverlay_force_respect_ttl | cheat | Default: false<br>Force respect TTL even when clearing scopes
debugoverlay_hide_imgui | sv, cheat | Hides the overlay.
debugoverlay_show_text_outline | cheat | Default: false<br>Toggle display of box around text
debugoverlay_text_scale | a, cheat | Default: 1<br>Scale of the text used for 3d display
debugoverlay_toggle | sv, cheat | Toggles visibility of the debug overlay system.
default_fov | cl, cheat | Default: 70<br>
demo_flush | a | Default: false<br>Flush writing the demo file every network update
demo_goto | release | Skips to location in demo.
demo_gotomark | release | Skips the current demo playback to the marked tick
demo_gototick | release | Skips to a tick in demo.
demo_info | release | Print information about currently playing demo.
demo_marktick | release | Marks the current demo playback tick for later use
demo_pause | release | Pauses demo playback.
demo_pauseatservertick | release | Pauses when the 'render time' reaches the specified tick.
demo_quitafterplayback | release | Default: false<br>Quits game after demo playback.
demo_recordcommands | cheat | Default: true<br>Record commands typed at console into .dem files.
demo_resume | release | Resumes demo playback.
demo_step_tick | release | Play for N ticks (default=1) and then pause.
demo_timescale | release | Sets demo replay speed.
demo_togglepause | release | Toggles demo playback.
demolist | release | Print demo sequence list.
developer | release | Default: 0<br>Set developer message level.
differences | release | Show all convars which are not at their default values (optional restricted to specific flags).
disable_dynamic_prop_loading | sv, cheat | Default: false<br>If non-zero when a map loads, dynamic props won't be loaded
disconnect | release | Disconnect from server
display_game_events | sv, cheat | Default: false<br>
dlight_debug | cl, cheat | Creates a dlight in front of the player
dota_enable_spatial_audio | release | Default: false<br>Flag to enable spatial audio in Dota 2.
dota_spatial_audio_mix | release | Default: 1<br>Mix value to blend spatial and non-spatial audio in Dota 2.
drawcross | sv, cheat | Draws a cross at the given location<br>	Arguments: x y z
drawline | sv, cheat | Draws line between two 3D Points.<br>	Green if no collision<br>	Red is collides with something<br>	Arguments: x1 y1 z1 x2 y2 z2
dsp_dist_max | cheat, demo | Default: 1440<br>
dsp_dist_min | cheat, demo | Default: 0<br>
dsp_off | cheat | Default: false<br>
dsp_volume | a, demo | Default: 0.8<br>
dump_entity_report | cl, cheat | List all client-side entities in the scene
dump_hero_names | cl, cheat | Lists all heroes by their technical names
dump_panorama_css_properties | release | Prints out all valid panorama CSS properties and their documentation
dump_panorama_events | release | print panorama event types and their documentation
dump_play_stats | sv, cheat | 
dumpparticlelist | cheat | Print out information on existing particle systems
echo | server_can_execute | Echo text to console.
echoln | release | Echo the command arguments on the console
enable_boneflex | cl, a | Default: true<br>
engine_low_latency_sleep_after_client_tick | release | Default: false<br>When r_low_latency is enabled, this moves the low latency sleep on tick frames to happen after client simulation.
engine_no_focus_sleep | a | Default: 20<br>
engine_show_frame_pacing | release | Default: false<br>
english | cl, user | Default: true<br>If set to 1, running the english language set of assets.
ent_absbox | sv, cheat | Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_actornames | sv, cheat | Displays the entity name for all entities that have ShouldDisplayInActorNames true in code
ent_actornames_font | sv, cl, rep, cheat | Default: Consolas<br>ent_actornames font name
ent_actornames_fontsize | sv, cl, rep, cheat | Default: 24<br>ent_actornames font size
ent_animgraph2_open_graph | sv, cheat | Opens the graph and starts live debugging the AG2 graph for a given entity<br>	Arguments: entityName<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_animgraph2_record | sv, cheat | Starts live debugging & recording the AG2 graph for a given entity<br>	Arguments: entityName<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_animgraph_debug | sv, cheat | Displays debug draws about the given entity(ies) animgraph<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_animgraph_record | sv, cheat | Toggles recording of animgraph replay of the given entity(s)<br>	Arguments: entityName automaticallyOpenInAnimgraphEditor<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_animgraph_setvar | sv, cheat | Sets a variable on the animgraph of the given entity(s)<br>	Arguments:   &lt;varname&gt;=&lt;value&gt;	&lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
ent_attachment_filter_substrings | sv, cheat | Default: <br>If an attachment's name has any of the given substrings in it, it will be displayed. Substrings can be delimited by the ',' or '\|' character.
ent_attachments | sv, cheat | Displays the attachment points on an entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_autoaim | sv, cheat | Displays the entity's autoaim radius.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_bbox | sv, cheat | Displays the movement bounding box for the given entity(ies) in orange.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_bonemergeplayer | sv, cheat | Bonemerge the player onto the entity under the crosshairs
ent_call | sv, cheat | ent_call &lt;funcname&gt; &lt;option:entname&gt; calls function on current look target or filtername, checks on ent, then root, then mode, then map scope
ent_clear_debug_overlays | sv, cheat | Clears all debug overlays
ent_create | sv, cheat | Creates an entity of the given designer or subclass name where the player is looking.
ent_find | sv, cheat | Find and list all entities with classnames or targetnames that contain the specified substrings.<br>Format: find_ent &lt;substring&gt;<br>
ent_find_index | sv, cheat | Display data for entity matching specified index.<br>Format: find_ent_index &lt;index&gt;<br>
ent_fire | sv, cheat | Usage:<br>   ent_fire &lt;target&gt; \[action\] \[value\] \[delay\]<br>
ent_fire_output | sv, cheat | Usage:<br>   ent_fire_output &lt;target&gt; \[output name\] \[value\] \[delay\]<br>
ent_gib | sv, cheat | Gibs the given entity(s)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_grab | sv, cheat | grabs the object in front of the player. Options: -loose -multiple -toggle
ent_hierarchy | sv, cheat | Prints the entity hierarchy tree rooted at the specified ent(s)
ent_hitbox | sv, cheat | Displays the hitboxes for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_info | sv, cheat | Usage:<br>   ent_info &lt;class name&gt;<br>
ent_joint_filter_substrings | sv, cheat | Default: <br>If a joint's name has any of the given substrings in it, it will be displayed. Substrings can be delimited by the ',' or '\|' character.
ent_joint_lines | sv, cheat | Default: true<br>Draw a line between a rendered joint and its parent.
ent_joint_names | sv, cheat | Default: true<br>Draw the name of a rendered joint.
ent_joints | sv, cheat | Displays the joint names + axes an entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_kill | sv, cheat | Kills the given entity(s)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_messages | sv, cheat | Toggles input/output message display for the selected entity(ies).  The name of the entity will be displayed as well as any messages that it sends or receives.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_messages_draw | sv, cl, rep, cheat | Default: false<br>Visualizes all entity input/output activity.
ent_name | sv, cheat | Displays the entity name
ent_orient | sv, cheat | Orient the specified entity to match the player's angles. By default, only orients target entity's YAW. Use the 'allangles' option to orient on all axis.<br>	Format: ent_orient &lt;entity name&gt; &lt;optional: allangles&gt;
ent_picker | sv, cheat | Toggles 'picker' mode.  When picker is on, the bounding box, pivot and debugging text is displayed for whatever entity the player is looking at.<br>	Arguments:	full - enables all debug information
ent_pivot | sv, cheat | Displays the pivot for the given entity(ies).<br>	(y=up=green, z=forward=blue, x=left=red). <br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_pivot_size | sv, a, cheat | Default: 20<br>
ent_rbox | cl, cheat | Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_remove | sv, cheat | Removes the given entity(s)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_remove_all | sv, cheat | Removes all entities of the specified type<br>	Arguments:   	{entity_name} / {class_name}
ent_rotate | sv, cheat | Rotates an entity by a specified # of degrees
ent_scale | sv, cheat | Scales entities.	Arguments: &lt;scale factor&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
ent_scenehierarchy | sv, cheat | Prints the entity scenenode hierarchy tree rooted at the specified ent(s)
ent_script_dump | sv, cheat | Dumps the names and values of this entity's script scope to the console<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_select | sv, cheat | Select or deselects the given entities(s) for later manipulation<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_setang | sv, cheat | Set entity angles
ent_setname | sv, cheat | Sets the targetname of the given entity(s)<br>	Arguments:   	&lt;new entity name&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
ent_setpos | sv, cheat | Move entity to position
ent_show_contexts | sv, cheat | Default: false<br>Show entity contexts in ent_text display
ent_show_damage | sv, cheat | Sets damage display mode.  When on, you will see the amount of damage dealt over the target's head.
ent_show_response_criteria | sv, cheat | Print, to the console, an entity's current criteria set used to select responses.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_showonlyattachment | sv, cheat | Default: <br>
ent_skeleton | sv, cheat | Displays the skeleton for the given entity(ies).<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_skeleton_duration | sv, cl, rep, cheat | Default: 0<br>Duration of ent_skeleton display
ent_teleport | sv, cheat | Teleport the specified entity to where the player is looking.<br>	Format: ent_teleport &lt;entity name&gt;
ent_text | sv, cheat | Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text256 | sv, cheat | Displays text debugging information about the given entity(ies) \[within 256 units of the player\] on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text_clear | sv, cheat | Hide text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text_filter | sv, cheat | Set which ent_text filters you want:
ent_text_flags_active | sv, a, cheat | Default: -1<br>
ent_text_no_name_really_i_mean_it | sv, cheat | Default: false<br>
ent_text_radius | sv, cheat | Displays text debugging information about the given entity(ies) \[near the player\] on top of the entity (See Overlay Text)<br>	2 Arguments:   	&lt;Radius&gt; &lt;{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}&gt;
ent_text_sticky_add | sv, cheat | Adds to list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text_sticky_clear | sv, cheat | Clears the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text_sticky_dump | sv, cheat | Spews the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_text_sticky_remove | sv, cheat | Removes from the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_ungrab | sv, cheat | un-grabs all objects
ent_vcollide_wireframe | sv, cheat | Displays the interpolated vcollide wireframe pm am entity.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_viewoffset | sv, cheat | Displays the eye position for the given entity(ies) in red.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
ent_visibility_traces | sv, cheat | Displays visibility traces for the given entity<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
entity_log_load_unserialize | sv, cl, rep, cheat | Default: 0<br>Output unserialization of entities on map load. 0 - off, 1 - client/server, 2 - server, 3 - client
escape | release, clientcmd_can_execute | Escape key pressed.
exec | norecord, release | Execute a cfg file
exec_async | cheat, norecord | Execute a cfg file over time
execifexists | norecord, release | Execute a cfg file if file exists
execute_command_every_frame | cheat | Default: <br>
experimental_citadel_tick_rate_override | sv, cl, rep, release | Default: 0<br>
explode | sv, cheat | Kills the player with explosive damage
explodevector | sv, cheat | Kills a player applying an explosive force. Usage: explodevector &lt;player&gt; &lt;x value&gt; &lt;y value&gt; &lt;z value&gt;
fadein | sv, cheat | fadein {time r g b}: Fades the screen in from black or from the specified color over the given number of seconds.
fadeout | sv, cheat | fadeout {time r g b}: Fades the screen to black or to the specified color over the given number of seconds.
find | release | Find concommands with the specified string in their name/help text.
findflags | release | Find concommands by flags.
firetarget | sv, cheat | 
firstperson | cl, release, per_tick | Switch to firstperson camera.
fish_debug | cl, cheat | Default: false<br>Show debug info for fish
fish_dormant | sv, rep, cheat | Default: false<br>Turns off interactive fish behavior. Fish become immobile and unresponsive.
fog_color | cl, cheat | Default: -1 -1 -1<br>
fog_colorskybox | cl, cheat | Default: -1 -1 -1<br>
fog_enable | cl, cheat | Default: true<br>Enable fog
fog_enableskybox | cl, cheat | Default: true<br>
fog_end | cl, cheat | Default: -1<br>
fog_endskybox | cl, cheat | Default: -1<br>
fog_hdrcolorscale | cl, cheat | Default: -1<br>
fog_hdrcolorscaleskybox | cl, cheat | Default: -1<br>
fog_maxdensity | cl, cheat | Default: -1<br>
fog_maxdensityskybox | cl, cheat | Default: -1<br>
fog_override | cl, cheat | Default: 0<br>Overrides the map's fog settings (-1 populates fog_ vars with map's values)
fog_override_color | cheat | Sets the fog color override
fog_override_enable | cheat | Default: false<br>Use fog_override convars instead of world fog data
fog_override_end | cheat | Default: 3500<br>
fog_override_exponent | cheat | Default: 2<br>
fog_override_max_density | cheat | Default: 0.4<br>
fog_override_start | cheat | Default: 1000<br>
fog_start | cl, cheat | Default: -1<br>
fog_startskybox | cl, cheat | Default: -1<br>
fov_desired | cl, a, user | Default: 75<br>Sets the base field-of-view.
fps_max | a, release | Default: 400<br>Frame rate limiter.  0=no limit.  Does not apply to dedicated server.
fps_max_tools | a | Default: 120<br>Additional frame rate limit while in tools mode and a window other than the game window has focus. Note that fps_max still applies, this only allows the maximum frame rate for tools mode to be lower. 0=no tools specific limit.
fps_max_ui | a | Default: 120<br>Frame rate limiter while the game UI is displayed.  0=no limit.  Does not apply to dedicated server.
fs_fake_read_delay_ms | release | Default: 0<br>Add N ms of delay to every low-level read operation, to simulate a slow disk
fs_report_sync_opens | release | Default: 0<br>0:Off, 1:Always, 2:Not during load
fs_spew_readfieldlist | cheat | index &lt;threshold bytes&gt;: spew changes to ent index, optionally only spewing if update is &gt; than threshold bytes
func_break_max_pieces | sv, a, rep | Default: 15<br>
g_debug_angularsensor | sv, cheat | Default: false<br>
g_debug_constraint_sounds | sv, cheat | Default: false<br>Enable debug printing about constraint sounds.
g_debug_ragdoll_visualize | cl, cheat | Default: false<br>
gameinstructor_dump_open_lessons | cl, cheat | Gives a list of all currently open lessons.
gameinstructor_dump_run_lesson_counts | cl, cheat | Gives a list of lessons that been completed or shown
gameinstructor_enable | cl, a, release | Default: true<br>Display in game lessons that teach new players.
gameinstructor_find_errors | cl, cheat | Default: false<br>Set to 1 and the game instructor will run EVERY scripted command to uncover errors.
gameinstructor_verbose | cl, cheat | Default: 0<br>Set to 1 for standard debugging or 2 (in combo with gameinstructor_verbose_lesson) to show update actions.
gameinstructor_verbose_lesson | cl, cheat | Default: <br>Display more verbose information for lessons have this name.
gameui_hide | release | Hides the game UI
getpos | cl, cheat | dump position and angles to the console
getpos_exact | cl, cheat | dump origin and angles to the console
getposcopy | cl, cheat | dump position and angles to the console and clipboard
getposcopy_exact | cl, cheat | dump origin and angles to the console and clipboard
give | sv | Give item to player.<br>	Arguments: &lt;item_name&gt;
give_oriented | sv | Give item oriented to player angles.<br>	Arguments: &lt;item_name&gt;
givecurrentammo | sv, cheat | Give a supply of ammo for current weapon..<br>
global_set | sv, cheat | global_set &lt;globalname&gt; &lt;state&gt;: Sets the state of the given env_global (0 = OFF, 1 = ON, 2 = DEAD).
glow_use_tolerance | cl, rep, cheat | Default: 0.85<br>
god | sv, cheat | Toggle by default, or 0 to disable and 1 to enable. Player becomes invulnerable.
grep | release | grep line for pattern, print out matching lines only
groups | sv, cheat | Show status of all spawn groups.
healme | sv, cheat | Heals the player.<br>	Arguments: &lt;health to gain&gt;
help | release | Find help about a convar/concommand.
hide_party_code | cl, a | Default: false<br>When set, this will hide the party code in the client
hideconsole | norecord, release | Hide the console.
host_framerate | release | Default: 0<br>Set to lock per-frame time elapse.
host_readconfig_ignore_userconfig | cheat | Default: false<br>Whether we should ignore the user config file for reading/writing.
host_timescale | rep, cheat | Default: 1<br>Prescale the clock by this amount.
host_timescale_dec | cheat | Decrement the timescale by one step
host_timescale_inc | cheat | Increment the timescale by one step
host_writeconfig | release | Saves out the user config values.
hostfile | sv, release | Default: host.txt<br>The HOST file to load.
hostip | release | Default: 0<br>Host game server ip
hostname | release | Default: <br>Hostname for server.
hostname_in_client_status | release | Default: false<br>Show server hostname in client status.
hostport | release | Default: 27015<br>Host game server port
hud_damagemeter | cl, cheat | Default: false<br>
hud_fastswitch | cl, a | Default: 0<br>
hud_free_cursor | cl, release | Default: -1<br>If -1 use the hud default, otherwise 0 is disabled, 1 is enabled
hud_free_cursor_toggle | cl, release | Toggles free cursor convar.
hud_minimap_spectator_fow_team_view_amber | cl, release | While a spectator, view team amber's minimap view
hud_minimap_spectator_fow_team_view_both_teams | cl, release | While a spectator, view both teams' minimap view
hud_minimap_spectator_fow_team_view_sapphire | cl, release | While a spectator, view team sapphire's minimap view
hud_minimap_spectator_fow_team_view_target_team | cl, release | While a spectator and viewing a player, view team their minimap view
hurtme | sv, cheat | Hurts the player.<br>	Arguments: &lt;health to lose&gt;
hurtthem | sv, cheat | Hurts the enemy in front of you.<br>	Arguments: &lt;health to lose&gt;
ik_debug_chain_to_filter_by | sv, cl, rep, cheat | Default: <br>
ik_enable | rep, cheat | Default: true<br>Enable IK.
ik_hinge_debug_bone_index | sv, cl, rep, cheat | Default: -1<br>
imgui_debug_entity | sv, cheat | Shows the entity browser, focused on the entity you specify.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
imgui_default_font_size | a, cheat | Default: 20<br>Default imgui font size
imgui_set_selection | sv, cheat | Sets ImGui selection
imgui_set_status_text | sv, cheat | Sets ImGui header status text
impulse | cl, release | Triggers impulse command
incrementvar | norecord, release | Increment specified convar value.
input_button_code_is_scan_code_scd | a, per_user | Default: true<br>Bind keys based on keyboard position instead of key name
input_filter_relative_analog_inputs | cl, a | Default: false<br>
input_forceuser | cheat | Default: -1<br>Force user input to this split screen player.
interesting_events_draw_debug | sv, cheat | Default: false<br>When enabled, draws a sphere representing active events
ip | release | Default: <br>Overrides IP for multihomed hosts
iv_debugbone | release | Default: <br>Debug bone name for interpolation spew of CAnimationState.
joy_advanced | cl, a | Default: false<br>
joy_advaxisr | cl, a | Default: 0<br>
joy_advaxisu | cl, a | Default: 0<br>
joy_advaxisv | cl, a | Default: 0<br>
joy_advaxisx | cl, a | Default: 0<br>
joy_advaxisy | cl, a | Default: 0<br>
joy_advaxisz | cl, a | Default: 0<br>
joy_axisbutton_threshold | a | Default: 0.3<br>Analog axis range before a button press is registered.
joy_axisr_deadzone | a, per_user | Default: 0.15<br>
joy_axisr_relative | a, per_user | Default: false<br>
joy_axisu_deadzone | a, per_user | Default: 0.15<br>
joy_axisu_relative | a, per_user | Default: false<br>
joy_axisv_deadzone | a, per_user | Default: 0.15<br>
joy_axisv_relative | a, per_user | Default: false<br>
joy_axisx_deadzone | a, per_user | Default: 0.15<br>
joy_axisx_relative | a, per_user | Default: false<br>
joy_axisy_deadzone | a, per_user | Default: 0.15<br>
joy_axisy_relative | a, per_user | Default: false<br>
joy_axisz_deadzone | a, per_user | Default: 0.15<br>
joy_axisz_relative | a, per_user | Default: false<br>
joy_circle_correct_mode | cl, a, per_user | Default: 1<br>
joy_circle_correct_mode_vehicle | cl, a, per_user | Default: 2<br>
joy_display_input | cl, a | Default: false<br>
joy_forward_sensitivity | cl, a, per_user | Default: 1<br>
joy_movement_stick | cl, a, per_user | Default: false<br>Which stick controls movement (0 is left stick)
joy_name | cl, a | Default: joystick<br>
joy_pitch_sensitivity | cl, a, per_user | Default: 3<br>
joy_pitchsensitivity | cl, a, per_user | Default: 1<br>
joy_response_look | cl, a, per_user | Default: 0<br>
joy_response_move | cl, a, per_user | Default: 9<br>
joy_side_sensitivity | cl, a, per_user | Default: 1<br>
joy_sidesensitivity | cl, a | Default: 1<br>
joy_yaw_sensitivity | cl, a, per_user | Default: 3<br>
joy_yawsensitivity | cl, a, per_user | Default: -1<br>
joystick | cl, a | Default: false<br>True if the joystick is enabled, false otherwise.
key_findbinding | release | Find key bound to specified command string.
key_listboundkeys | release | List bound keys with bindings.
kick | norecord, release | Kick a player by name.
kickid | norecord, release | Kick a player by userid or uniqueid, with a message.
kickid_hltv | norecord, release | Kick a player by userid or uniqueid, with a message.
kill | sv, cheat | Kills the player with generic damage
kill_all_shrines | sv, cheat, release | Kills all shrines
killvector | sv, cheat | Kills a player applying force. Usage: killvector &lt;player&gt; &lt;x value&gt; &lt;y value&gt; &lt;z value&gt;
labelled_debug_helper_arc_segments | sv, cl, rep, cheat | Default: 20<br>
labelled_debug_helper_enabled | sv, cl, rep, cheat | Default: true<br>
labelled_debug_helper_scale | sv, cl, rep, cheat | Default: 1<br>
labelled_debug_helper_show_position | sv, cl, rep, cheat | Default: false<br>
labelled_debug_helper_show_text | sv, cl, rep, cheat | Default: true<br>
labelled_debug_helper_skeleton_show_bone_names | sv, cl, rep, cheat | Default: true<br>
last_viewed_announce_id | cl, a | Default: -1<br>Tracks the last announcement ID viewed so we can know when new announcements are available
lb_barnlight_shadowmap_scale | release | Default: 1<br>Scale for computed barnlight shadowmap size
lb_shadow_map_cull_empty_mixed | cheat | Default: false<br>Don't render shadows for mixed shadowmaps with no dynamics objects in view
lb_shadow_map_culling | cheat | Default: true<br>
lightquery_debug_direct_lighting | sv, cl, rep, cheat | Default: true<br>
lightquery_debug_indirect_lighting | sv, cl, rep, cheat | Default: true<br>
listdemo | release | List demo file contents.
log | release | Enables logging to file, console, and udp &lt; on \| off &gt;.
log_color | norecord, release | Set the color of a logging channel.
log_dumpchannels | norecord, release | Dumps information about all logging channels.
log_flags | norecord, release | Set the flags on a logging channel.
log_level | norecord, release | Set the spew level of a logging channel.
log_verbosity | norecord, release | Set the verbosity of a logging channel.
logic_npc_counter_debug | sv, rep, cheat | Default: false<br>
m_pitch | cl, a, user, per_user | Default: 0.022<br>Mouse pitch factor.
m_yaw | cl, a, user, per_user | Default: 0.022<br>Mouse yaw factor.
map | release | map &lt;mapname&gt; :Load a new map.
map_enable_portrait_worlds | cl, cheat | Enables/disables portrait worlds
maps | release | Displays list of maps.
markup_group_ent_bbox | sv, cheat | markup_group_ent_bbox &lt;markup_group name&gt; -&gt; toggle ent_bbox for all members of the named markup group
markup_group_ent_text | sv, cheat | markup_group_ent_text &lt;markup_group name&gt; -&gt; toggle ent_text for all members of the named markup group
markup_group_spew | sv, cheat | Spew all current markup groups and their members
mat_async_shader_load | release | Default: false<br>
mat_colcorrection_forceentitiesclientside | cl, cheat | Default: false<br>Forces color correction entities to be updated on the client
mat_fullbright | cheat | Default: 0<br>Debug rendering modes
mat_lpv_luxels | cheat | Default: false<br>
mat_luxels | cheat | Default: false<br>
mat_max_lighting_complexity | cheat | Default: 8<br>
mat_overdraw | cheat | Default: 0<br>Visualize overdraw
mat_overdraw_color | cheat | Default: 0.075 0.15 0.3<br>
mat_shading_complexity | cheat | Default: false<br>Visualize shading complexity
mat_shading_complexity_color | cheat | Default: 1 0.5 0.25<br>
mat_shading_complexity_max_instruction_count | cheat | Default: 1024<br>
mat_shading_complexity_max_register_count | cheat | Default: 128<br>
mat_shadowmap_luxels | cheat | Default: false<br>
mat_show_distance_field | cheat | Default: 0<br>0=Off, 1=Visualize trace from camera, 2=Visualize occlusion, 3=Visualize far field trace from camera
mat_tonemap_bloom_scale | cheat | Default: -1<br>
mat_tonemap_bloom_start_value | cheat | Default: -1<br>
mat_tonemap_force_accelerate_exposure_down | cheat | Default: -1<br>
mat_tonemap_force_average_lum_min | cheat | Default: -1<br>Override. Old default was 3.0
mat_tonemap_force_log_lum_max | cheat | Default: -1<br>
mat_tonemap_force_log_lum_min | cheat | Default: -1<br>
mat_tonemap_force_max | cheat | Default: -1<br>
mat_tonemap_force_min | cheat | Default: -1<br>
mat_tonemap_force_percent_bright_pixels | cheat | Default: -1<br>Override. Old value was 1.0
mat_tonemap_force_percent_target | cheat | Default: -1<br>Override. Old default was 45.
mat_tonemap_force_rate | cheat | Default: -1<br>
mat_tonemap_force_scale | cheat | Default: 0<br>
mat_tonemap_force_use_alpha | cheat | Default: -1<br>
mat_tonemap_uncap_exposure | cheat | Default: 0<br>
mat_wireframe | cheat | Default: 0<br>0=Off, 1=Surface Wireframe, 2=Transparent Wireframe
mesh_calculate_curvature_smooth_invert | sv, cl, rep, cheat | Default: false<br>
mesh_calculate_curvature_smooth_pass_count | sv, cl, rep, cheat | Default: 3<br>
mesh_calculate_curvature_smooth_weight | sv, cl, rep, cheat | Default: 1<br>
minimap_update_rate_hz | sv, release | Default: 30<br>
minimap_zoom_in | cl, release | Ping button pressed
minimap_zoom_out | cl, release | Ping button released
mm_prefer_solo_only | cl, a, release | Default: false<br>Prefer being matched with other solo players when not in a party
mobile_fps_increase_during_charging | a | Default: false<br>MOBILE_FPS_CONTROL: If true we increase framerate limit while charging
mobile_fps_increase_during_touch | a | Default: true<br>MOBILE_FPS_CONTROL: If true we increase framerate limit during touch
mobile_fps_limit | a | Default: 30<br>MOBILE_FPS_CONTROL: Mobile FPS limit - 15, 30, 60
mod_status | cl, release | &lt;Account ID&gt;
model_default_preview_sequence_name | sv, cl, a, rep | Default: <br>
modifier_aura_debug | sv, cl, rep, cheat | Default: false<br>Set to 1 to draw the radii of all active auras
modifier_create | sv, cheat | Creates a test modifier on unit: modifier_create &lt;entityindex&gt; &lt;modifiername&gt; &lt;duration&gt;
modifier_dump | sv, cheat | Display all modifiers for the unit: &lt;entityindex/name&gt;
modifier_dump_list | sv, cheat | Dumps all modifiers that exist in the game
modifier_dump_visible | sv, cheat | Print out non-hidden modifiers.
modifier_remove | sv, cheat | Removes the first modifier that matches the name from a unit: modifier_remove &lt;entityindex&gt; &lt;modifiername&gt;
modifier_spew_states | sv, cheat | Call to have the client spew their unit states affecting them,
modifier_stringtable_dump | sv, cheat | Displays the contents of the modifier string table
modifier_test_scripted_event | sv, cheat | Tests firing a scripted event
modifier_test_scripted_event_end | sv, cheat | Tests firing ending a scripted event
motdfile | sv, release | Default: motd.txt<br>The MOTD file to load.
mouse_inverty | cl, a, user | Default: false<br>
movement_stats_debug_draw | sv, cheat | Default: false<br>
movement_stats_force_calculate | sv, cheat | Default: false<br>
mp_disable_autokick | sv, release | Prevents a userid from being auto-kicked
mp_forcecamera | sv, cl, rep, release | Default: 0<br>Restricts spectator modes for dead players
mp_friendlyfire | sv, cl, nf, rep, release | Default: false<br>Allows team members to injure other members of their team
mp_restartgame | sv, release | Default: 0<br>If non-zero, game will restart in the specified number of seconds
multvar | norecord, release | Multiply specified convar value.
name | a, per_user | Default: unnamed<br>
nav_add_to_selected_set | sv, cheat | Add current area to the selected set.
nav_add_to_selected_set_by_id | sv, cheat | Add specified area id to the selected set.
nav_begin_deselecting | sv, cheat | Start continuously removing from the selected set.
nav_begin_drag_deselecting | sv, cheat | Start dragging a selection area.
nav_begin_drag_selecting | sv, cheat | Start dragging a selection area.
nav_begin_selecting | sv, cheat | Start continuously adding to the selected set.
nav_bfs_debug | sv, cheat | Default: 0<br>
nav_clear_attribute | sv, cheat | Remove given nav attribute from all areas in the selected set.
nav_clear_attributes | sv, cheat | Clear all nav attributes of selected area.
nav_clear_selected_set | sv, cheat | Clear the selected set.
nav_corner_adjust_adjacent | cheat | Default: 18<br>radius used to raise/lower corners in nearby areas when raising/lowering corners.
nav_create_indirect_connection | sv, cheat | Create a connection between the selected area and the area pointed at by the crosshair.
nav_create_indirect_connection_from_to | sv, cheat | Create a connection between the current 'from' and 'to' locations.
nav_create_indirect_connection_set_from | sv, cheat | Default: 0 0 0<br>Set the 'from' location of an indirect connection.
nav_create_indirect_connection_set_from_using_editpos | sv, cheat | Set the 'from' location of an indirect connection to be the current edit pos of nav_edit.
nav_create_indirect_connection_set_to | sv, cheat | Default: 0 0 0<br>Set the 'to' location of an indirect connection.
nav_create_indirect_connection_set_to_using_editpos | sv, cheat | Set the 'to' location of an indirect connection to be the current edit pos of nav_edit.
nav_curve_alt | sv, cheat | Default: false<br>
nav_curve_iter | sv, cheat | Default: 0<br>
nav_curve_lock | sv, cheat | Default: -1<br>
nav_curve_max_step | sv, cheat | Default: 10<br>
nav_curve_set | sv, cheat | Default: -1<br>
nav_curve_step | sv, cheat | Default: 0.02<br>
nav_debug_blocked | sv, cheat | Default: false<br>
nav_delete | sv, cheat | Deletes the currently highlighted Area.
nav_draw_area_connections | sv, cheat | Default: false<br>
nav_draw_area_filled | sv, cheat | Default: true<br>
nav_draw_area_gravity | sv, cheat | Default: false<br>
nav_draw_area_ground | sv, cheat | Default: false<br>
nav_draw_area_hull_support | sv, cheat | Default: false<br>
nav_draw_area_ids | sv, cheat | Default: false<br>
nav_draw_area_inset_margin | sv, cheat | Default: 0<br>
nav_draw_area_normal | sv, cheat | Default: false<br>
nav_draw_area_should_be_destroyed | sv, cheat | Default: false<br>
nav_draw_area_split_by_obstacle_mgr | sv, cheat | Default: false<br>
nav_draw_area_ztest | sv, cheat | Default: false<br>
nav_draw_blocked | sv, cheat | Default: true<br>
nav_draw_blocked_connections | sv, cheat | Default: false<br>
nav_draw_boundary_areas | sv, cheat | Default: false<br>
nav_draw_connected_area_radius | sv, cheat | Default: 1000<br>
nav_draw_dormant_movable_meshes | sv, cheat | Default: false<br>Draw dormant movable meshes.
nav_draw_externally_created | sv, cheat | Default: false<br>
nav_draw_flow_map | sv, cheat | Default: false<br>
nav_draw_indirect_connections | sv, cheat | Default: false<br>
nav_draw_jump_links | sv, cheat | Default: false<br>
nav_draw_limit | sv, cheat | Default: 300<br>The maximum number of areas to draw in edit mode
nav_draw_link_alignment | sv, cheat | Default: false<br>
nav_draw_links | sv, cheat | Default: false<br>
nav_draw_markup | sv, cheat | Default: true<br>
nav_draw_mesh | sv, cheat | Default: true<br>
nav_draw_mesh_grid | sv, cheat | Default: false<br>Draw the mesh's spatial grid structure around the edit cursor position.
nav_draw_mesh_offset | sv, cheat | Default: 1<br>Vertical offset for drawing the mesh (useful for flat planes where the mesh is often a fixed offset from the physical ground
nav_edit | sv, cheat | Default: 0<br>Set to one to interactively edit the Navigation Mesh. Set to zero to leave edit mode.
nav_edit_use_camera | sv, cheat | Default: true<br>
nav_edit_validate | sv, cheat | Default: false<br>Validate navmesh structures.
nav_end_deselecting | sv, cheat | Stop continuously removing from the selected set.
nav_end_drag_deselecting | sv, cheat | Stop dragging a selection area.
nav_end_drag_selecting | sv, cheat | Stop dragging a selection area.
nav_end_selecting | sv, cheat | Stop continuously adding to the selected set.
nav_find_occluded_node_nozup_use_raycast | sv, cheat | Default: true<br>
nav_gen_add_jumps | sv, cheat | Default: true<br>
nav_gen_agent_radius_buffer | sv, cheat | Default: 0.5<br>Buffer to add to agent radius before passing to nav gen
nav_gen_clip_polys_to_clearance | sv, cheat | Default: true<br>
nav_gen_clip_polys_to_clearance_debug | sv, cheat | Default: false<br>
nav_gen_connect_allow_multiple | sv, cheat | Default: true<br>
nav_gen_connect_angle | sv, cheat | Default: 0.75<br>
nav_gen_connect_angle_ignore_z | sv, cheat | Default: true<br>
nav_gen_connect_dist_a | sv, cheat | Default: 1<br>
nav_gen_connect_dist_b | sv, cheat | Default: 1.5<br>
nav_gen_connect_dist_z_mult | sv, cheat | Default: 0.5<br>
nav_gen_connect_overlap | sv, cheat | Default: 0.5<br>
nav_gen_degen_limit | sv, cheat | Default: 0.001<br>
nav_gen_false | sv, cheat | Default: false<br>Always false
nav_gen_island_removal | sv, cheat | Default: false<br>
nav_gen_island_removal_all_hulls | sv, cheat | Default: true<br>
nav_gen_join_nonzup | sv, cheat | Default: true<br>
nav_gen_jump_connection_min_overlap_ratio | sv, cheat | Default: 1<br>Minimum edge overlap required for jump connection consideration as a percentage of agent radius
nav_gen_markup_split_expand | sv, cheat | Default: 2<br>
nav_gen_markup_split_tol_base | sv, cheat | Default: 1<br>
nav_gen_markup_split_tol_nonav | sv, cheat | Default: 1<br>
nav_gen_markup_split_tol_nonentity | sv, cheat | Default: 8<br>
nav_gen_max_bottleneck_width | sv, cheat | Default: 128<br>
nav_gen_max_bottleneck_width_do_clip | sv, cheat | Default: true<br>
nav_gen_max_edge_len | sv, cheat | Default: 512<br>
nav_gen_max_edge_len_do_clip | sv, cheat | Default: true<br>
nav_gen_max_edge_len_split_tol | sv, cheat | Default: 24<br>
nav_gen_opt_to_quads | sv, cheat | Default: true<br>
nav_gen_opt_to_quads_angle_limit | sv, cheat | Default: 8<br>
nav_gen_opt_to_quads_num_steps | sv, cheat | Default: 6<br>
nav_gen_opt_to_quads_planar_deviation_limit | sv, cheat | Default: 4<br>
nav_gen_opt_to_quads_se_limit_end | sv, cheat | Default: 0.1<br>
nav_gen_opt_to_quads_se_limit_start | sv, cheat | Default: 1e-05<br>
nav_gen_opt_to_quads_weld_limit_end | sv, cheat | Default: 0.01<br>
nav_gen_opt_to_quads_weld_limit_start | sv, cheat | Default: 1e-07<br>
nav_gen_oriented_angle_tol | sv, cheat | Default: 15<br>Max abrupt orientation difference an NPC can tolerate when moving through the mesh (degrees).
nav_gen_oriented_max_region_range | sv, cheat | Default: 15<br>Max orientation range allowed within a region before it gets further split.
nav_gen_remove_vertical_polys | sv, cheat | Default: true<br>
nav_gen_split_boundary_polys | sv, cheat | Default: false<br>
nav_gen_split_multi_connection_polys | sv, cheat | Default: true<br>
nav_gen_split_multi_connection_polys_tol | sv, cheat | Default: 0.01<br>
nav_gen_true | sv, cheat | Default: true<br>Always true
nav_gen_vertical_limit | sv, cheat | Default: 88<br>
nav_genrt_debug | sv, cheat | Default: false<br>
nav_gm_enable | sv, cheat | Default: false<br>
nav_list_movable_meshes | sv, cheat | List the movable meshes registered with the movable meshes manager.
nav_lower_drag_volume_max | sv, cheat | Lower the top of the drag select volume.
nav_lower_drag_volume_min | sv, cheat | Lower the bottom of the drag select volume.
nav_mark | sv, cheat | Marks the Area or Ladder under the cursor for manipulation by subsequent editing commands.
nav_mark_attribute | sv, cheat | Set nav attribute for all areas in the selected set.
nav_max_vis_delta_list_length | cheat | Default: 64<br>
nav_obstacle_validate | sv, cheat | Default: false<br>
nav_obstruction_draw | sv, cheat | Default: 0<br>
nav_obstruction_draw_change | sv, cheat | Default: false<br>
nav_obstruction_draw_dist | sv, cheat | Default: -1<br>
nav_obstruction_draw_island | sv, cheat | Default: 0<br>
nav_obstruction_draw_island_hull | sv, cheat | Default: -1<br>
nav_obstruction_draw_movefail_blocking | sv, cheat | Default: false<br>
nav_path_debug | sv, cheat | Default: false<br>
nav_path_draw_areas | sv, cheat | Default: false<br>
nav_path_draw_arrow | sv, cheat | Default: true<br>
nav_path_draw_climb_segments | sv, cheat | Default: true<br>
nav_path_draw_connected_areas | sv, cheat | Default: false<br>
nav_path_draw_ground_segments | sv, cheat | Default: true<br>
nav_path_draw_jump_segments | sv, cheat | Default: true<br>
nav_path_draw_ladder_segments | sv, cheat | Default: true<br>
nav_path_draw_link_segments | sv, cheat | Default: true<br>
nav_path_draw_tick | sv, cheat | Default: 0<br>
nav_path_fixup_climb_up_segments | sv, cheat | Default: true<br>
nav_path_fixup_gap_segments | sv, cheat | Default: false<br>
nav_path_jump_process_debug | sv, cheat | Default: false<br>
nav_path_optimize | sv, cheat | Default: true<br>
nav_path_optimize_portals | sv, cheat | Default: true<br>
nav_path_optimizer_debug | sv, cheat | Default: 0<br>
nav_pathfind_debug_log | sv, cheat | Default: 0<br>
nav_pathfind_draw | sv, cheat | Default: 0<br>
nav_pathfind_draw_blocked | sv, cheat | Default: 0<br>
nav_pathfind_draw_costs | sv, cheat | Default: false<br>
nav_pathfind_draw_fail | sv, cheat | Default: 0<br>
nav_pathfind_draw_total_costs | sv, cheat | Default: false<br>
nav_pathfind_inadmissable_heuristic_factor | sv, cheat | Default: 1<br>
nav_pathfind_multithread | sv, cheat | Default: false<br>
nav_raise_drag_volume_max | sv, cheat | Raise the top of the drag select volume.
nav_raise_drag_volume_min | sv, cheat | Raise the bottom of the drag select volume.
nav_recall_selected_set | sv, cheat | Re-selects the stored selected set.
nav_recorder_enabled | sv, cheat | Default: true<br>
nav_remove_from_selected_set | sv, cheat | Remove current area from the selected set.
nav_select_allow_blocked | sv, cheat | Default: true<br>When selecting an area under nav_edit, allow area marked as blocked.
nav_select_area_id | sv, cheat | Default: -1<br>Select nav area with matching ID.
nav_select_block_id | sv, cheat | Default: -1<br>Select nav space block with matching ID.
nav_select_hull | sv, cheat | Default: 0<br>Restrict area selection to areas that can support a hull of the given category
nav_select_radius | sv, cheat | Adds all areas in a radius to the selection set
nav_select_with_attribute | sv, cheat | Selects areas with the given attribute.
nav_set_movable_mesh_dormant_flag | sv, cheat | Set the movable mesh dormant flag (0=active, 1=dormant)
nav_show_area_connections | sv, cheat | Default: true<br>Show connections to selected area when true
nav_show_area_verts | sv, cheat | Default: true<br>Show area vertex positions
nav_show_area_water_info | sv, cheat | Default: true<br>
nav_show_elem_info | sv, cheat | Default: true<br>
nav_show_elem_info_font | sv, cheat | Default: Consolas<br>
nav_show_elem_info_font_size | sv, cheat | Default: -1<br>
nav_show_elem_info_font_voffset | sv, cheat | Default: -11<br>
nav_show_potentially_visible | cheat | Default: 0<br>Show areas that are potentially visible from the current nav area
nav_smooth_constrain_spline | sv, cheat | Default: true<br>
nav_smooth_constrain_spline_relax | sv, cheat | Default: 0.006<br>
nav_smooth_constrain_spring | sv, cheat | Default: 2<br>
nav_smooth_constrain_spring_relax | sv, cheat | Default: 0.01<br>
nav_smooth_draw_boundary | sv, cheat | Default: 0<br>
nav_smooth_draw_calc | sv, cheat | Default: 0<br>
nav_smooth_draw_constraint_spline | sv, cheat | Default: false<br>
nav_smooth_draw_constraint_spring | sv, cheat | Default: 0<br>
nav_smooth_draw_speed | sv, cheat | Default: 0<br>
nav_smooth_enable | sv, cheat | Default: true<br>
nav_smooth_relax | sv, cheat | Default: true<br>
nav_smooth_relax_use_timesteps | sv, cheat | Default: false<br>
nav_smooth_spring_const_override | sv, cheat | Default: -1<br>
nav_smooth_spring_enable | sv, cheat | Default: true<br>
nav_smooth_spring_factor_deriv | sv, cheat | Default: 0<br>
nav_smooth_spring_factor_dist | sv, cheat | Default: 0<br>
nav_smooth_spring_factor_speed | sv, cheat | Default: 0<br>
nav_smooth_spring_forward_dist_base | sv, cheat | Default: 50<br>
nav_smooth_spring_forward_dist_time_limit | sv, cheat | Default: 1<br>
nav_smooth_spring_max_dist | sv, cheat | Default: 36<br>
nav_smooth_spring_tension_max_override | sv, cheat | Default: -1<br>
nav_smooth_spring_timestep_factor_accel | sv, cheat | Default: 100<br>
nav_smooth_spring_timestep_factor_speed | sv, cheat | Default: 100<br>
nav_smooth_spring_timestep_max | sv, cheat | Default: 0.5<br>
nav_smooth_spring_timestep_min | sv, cheat | Default: 0.1<br>
nav_smooth_spring_yaw_rotation_speed | sv, cheat | Default: 50<br>
nav_smooth_spring_yaw_threshold | sv, cheat | Default: 20<br>
nav_space_select_dist | sv, cheat | Default: 1000<br>
nav_split | sv, cheat | To split an Area into two, align the split line using your cursor and invoke the split command.
nav_split_show_line | sv, cheat | Default: false<br>Show the free split line.
nav_store_selected_set | sv, cheat | Stores the current selected set for later retrieval.
nav_test_area_gravity | sv, cheat | Default: false<br>
nav_test_bfs_lattice_dist_0 | sv, cheat | Default: -1<br>
nav_test_bfs_lattice_dist_1 | sv, cheat | Default: -1<br>
nav_test_bfs_lattice_dist_2 | sv, cheat | Default: -1<br>
nav_test_bfs_lattice_hex | sv, cheat | Default: false<br>Demonstrates searching hexagonal lattice over nav mesh.
nav_test_bfs_lattice_mark | sv, cheat | Default: 2<br>
nav_test_bfs_lattice_simple | sv, cheat | Default: false<br>
nav_test_bfs_lattice_spacing_0 | sv, cheat | Default: 24<br>
nav_test_bfs_lattice_spacing_1 | sv, cheat | Default: 48<br>
nav_test_bfs_lattice_spacing_2 | sv, cheat | Default: 96<br>
nav_test_bfs_simple | sv, cheat | Default: false<br>
nav_test_boundary_zone_circle | sv, cheat | Default: 0<br>
nav_test_boundary_zone_force | sv, cheat | Default: false<br>
nav_test_boundary_zone_grid_dim | sv, cheat | Default: 90<br>
nav_test_boundary_zone_path | sv, cheat | Default: 0<br>
nav_test_boundary_zone_rays | sv, cheat | Default: 100<br>
nav_test_boundary_zone_rays_margin | sv, cheat | Default: -1<br>
nav_test_boundary_zone_rays_random | sv, cheat | Default: false<br>
nav_test_boundary_zone_sphere | sv, cheat | Default: 0<br>
nav_test_curve_opt | sv, cheat | Default: 0<br>
nav_test_detour | sv, cheat | Default: false<br>
nav_test_find_nearest | sv, cheat | Default: false<br>Calculate the nearest point on the navmesh to the trace point.  Uses selection from nav_select_hull.
nav_test_find_nearest_clear | sv, cheat | Default: false<br>Calculate the nearest point on the navmesh to the trace point.  Uses selection from nav_select_hull.
nav_test_find_random_connected | sv, cheat | Default: false<br>Demonstrates finding random points that are connected in the nav mesh to the start point.
nav_test_find_random_connected_dist_max | sv, cheat | Default: 1000<br>
nav_test_find_random_connected_dist_min | sv, cheat | Default: 100<br>
nav_test_find_z | sv, cheat | Default: 0<br>
nav_test_force_npc_repath | sv, cheat | Default: false<br>
nav_test_genrt | sv, cheat | Default: false<br>
nav_test_genrt_place | sv, cheat | Default: false<br>
nav_test_genrt_tile_removal_extent | sv, cheat | Default: 50<br>
nav_test_genrt_tile_removal_place | sv, cheat | Default: false<br>
nav_test_getareaoverlapping_gravity | sv, cheat | Default: false<br>
nav_test_getnearestnav_gravity | sv, cheat | Default: false<br>
nav_test_level_hull | sv, cheat | Find entities that intrude into the nav mesh.  List those entities in console output, and display bounding boxes around them for a while.
nav_test_level_hull_move | sv, cheat | 
nav_test_multi_connection | sv, cheat | Default: false<br>
nav_test_npc_area | sv, cheat | Default: 0<br>
nav_test_npc_collision | sv, cheat | Default: 0<br>
nav_test_npc_collision_range | sv, cheat | Default: 250<br>
nav_test_npc_collision_show_geometry | sv, cheat | Default: false<br>
nav_test_path | sv, cheat | Default: false<br>Calculate and draw a path from player/camera position to the test position.
nav_test_path_expansion_search | sv, cheat | Default: 0<br>Extend nav_test_path by doing an expansion search on that path.  Convar value defines dist.
nav_test_path_lock_goal | sv, cheat | Default: false<br>Lock the pathfinding goal to the current intersection point.
nav_test_path_lock_start | sv, cheat | Default: false<br>Lock the pathfinding start to the current intersection point.
nav_test_path_move | sv, cheat | Default: false<br>
nav_test_path_opt | sv, cheat | Default: true<br>Enable path optimization for nav_edit_path paths.
nav_test_path_opt_transitions | sv, cheat | Default: false<br>
nav_test_path_return | sv, cheat | Default: false<br>Calculate a return path from cursor position to the path calculated by nav_test_path.
nav_test_path_space | sv, cheat | Default: 0<br>Should nav_test_path test 3d navigation?  1 = space to space, 2 = multi-modal space/ground
nav_test_path_space_fly | sv, cheat | Default: true<br>Test flight paths
nav_test_path_space_swim | sv, cheat | Default: true<br>Test swim paths
nav_test_ray_space | sv, cheat | Default: 0<br>
nav_test_rays | sv, cheat | Default: false<br>
nav_test_smooth | sv, cheat | Default: false<br>
nav_test_smooth_extern_push | sv, cheat | Default: 0<br>
nav_test_smooth_in_speed | sv, cheat | Default: 120<br>
nav_test_smooth_in_yaw | sv, cheat | Default: 0<br>
nav_test_smooth_path_speed | sv, cheat | Default: -1<br>
nav_test_smooth_separating_dist | sv, cheat | Default: -1<br>
nav_test_smooth_spring_const | sv, cheat | Default: -1<br>
nav_test_smooth_spring_tension_max | sv, cheat | Default: -1<br>
nav_test_spline | sv, cheat | Default: 0<br>
nav_test_split_obstacle | sv, cheat | Default: 0<br>
nav_test_split_obstacle_dirty | sv, cheat | Default: false<br>
nav_test_split_obstacle_leave | sv, cheat | Default: false<br>
nav_test_split_obstacle_size | sv, cheat | Default: 30<br>
nav_test_split_obstacle_update_pos | sv, cheat | Default: true<br>
nav_toggle_deselecting | sv, cheat | Start or stop continuously removing from the selected set.
nav_toggle_in_selected_set | sv, cheat | Remove current area from the selected set.
nav_toggle_selected_set | sv, cheat | Toggles all areas into/out of the selected set.
nav_toggle_selecting | sv, cheat | Start or stop continuously adding to the selected set.
nav_unmark | sv, cheat | Clears the marked Area or Ladder.
nav_validate | cheat | Default: 0<br>Level of validation for nav system.  Higher will be slower.
nav_volume_debug | sv, cheat | Default: 0<br>Draw or print debug information about nav volume queries.
navspace_create_water_smooth_connections | sv, cheat | Default: true<br>
navspace_create_water_transition_connections | sv, cheat | Default: true<br>
navspace_debug_pathfind | sv, cheat | Default: -1<br>
navspace_debug_stringpull | sv, cheat | Default: 1<br>
navspace_debug_trace | sv, cheat | Default: 0<br>
navspace_debug_transition_calc | sv, cheat | Default: 0<br>
navspace_draw_changes_blocks | sv, cheat | Default: 0<br>Draw blocks when they change
navspace_draw_changes_waters | sv, cheat | Default: 0<br>Draw water volumes when they change
navspace_path_use_water_level_locator | sv, cheat | Default: true<br>
net_channels | release | Shows net channel info
net_connections_stats | release | Print detailed network statistics for each network connection
net_fakeclear | release | Clear all simulated network conditions
net_fakejitter | release | Shortcut to set jitter net options.  Run with no arguments for usage.
net_fakelag | release | Shortcut to set both FakePacketLag_Recv and FakePacketLag_Send net options
net_fakeloss | release | Shortcut to set both FakePacketLoss_Recv and FakePacketLoss_Send net options
net_fakestatus | release | Print current simulated network condifions
net_limit_sv_recv_max_message_size_kb | release | Default: 32<br>Server will reject message larger than N kb
net_limit_sv_recv_segments_per_packet | release | Default: 50<br>Server will reject packets with more than N segments
net_limit_sv_recvbuffer_kb | release | Default: 128<br>Server will not buffer more than N kb from connected clients
net_limit_sv_recvbuffer_msg | release | Default: 100<br>Server will not buffer more than N messages from connected clients
net_listallmessages | cheat | List all registered net messages
net_messageinfo | cheat | Display info about a message (by classname or id)
net_option | release | Get or set SteamNetworkingSockets options such as fake packet lag and loss
net_print_sdr_ping_times | release | Print current ping times to SDR points of presence, and selected route
net_public_adr | release | Default: <br>For servers behind NAT/DHCP meant to be exposed to the public internet, this is the public facing ip address string: ("x.x.x.x" )
net_showudp | release | Default: false<br>Dump UDP packets summary to console
net_showudp_remoteonly | release | Default: true<br>Dump non-loopback udp only
net_status | release | Shows current network status
net_validatemessages | cheat | Activates/deactivates net message validation
nextdemo | release | Play next demo in sequence.
noclip | sv, cheat | Toggle. Player becomes non-solid and flies.  Optional argument of 0 or 1 to force enable/disable
noclip_fixup | sv, cheat | Default: true<br>
notarget | sv, cheat | Toggle. Player becomes hidden to NPCs.
npc_ability_range_debug | sv, cheat | Draws range indicators for abilities for the given NPC(s).  Uses the NPCs enemy for range drawing.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_bodylocations | sv, cheat | Displays labelled body locations of NPCs.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_combat | sv, cheat | Displays text debugging information about the squad and enemy of the selected NPC  (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_conditions | sv, cheat | Displays all the current AI conditions that an NPC has in the overlay text.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_conditions_text | sv, cheat | Outputs text debugging information to the console about the all condition gathering for the selected NPC current schedule<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_create | sv, cheat | Creates an NPC of the given type where the player is looking (if the given NPC can actually stand at that location).  <br>	Arguments:	\[npc_class_name\] \[name of npc (optional) \] \[addon type (optional) \] \[name of addon (optional) \]
npc_create_aimed | sv, cheat | Creates an NPC aimed away from the player of the given type where the player is looking (if the given NPC can actually stand at that location).  Note that this only works for npc classes that are already in the world.  You can not create an entity that doesn't have an instance in the level.<br>	Arguments:	{npc_class_name}
npc_create_or_teleport_warn_on_nonav | sv, cheat | Default: true<br>Warn if the created or teleported npc is off nav.
npc_damage | sv, cheat | Deals the target damage by the given amount
npc_destroy | sv, cheat | Removes the given NPC(s) from the universe<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_destroy_unselected | sv, cheat | Removes all NPCs from the universe that aren't currently selected
npc_enemies | sv, cheat | Shows memory of NPC.  Draws an X on top of each memory.<br>	Eluded entities drawn in blue (don't know where it went)<br>	Unreachable entities drawn in green (can't get to it)<br>	Current enemy drawn in red<br>	Current target entity drawn in magenta<br>	All other entities drawn in pink<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_go | sv, cheat | Selected NPC(s) will go to the location that the player is looking (shown with a purple box)<br>	Arguments: &lt;start x y z&gt; &lt;goal x y z&gt;
npc_go_last | sv, cheat | Go to the last position you told an NPC to go.
npc_go_loop | sv, cheat | Toggles whether the selected NPC(s) will loop between the last set of waypoints you used 'npc go' on.
npc_go_loop_clear_waypoints | sv, cheat | Clear waypoints for npc_go_loop.
npc_go_no_arrow | sv, a | Default: false<br>Don't draw the go arrow of selected NPCs
npc_go_random | sv, cheat | Sends all selected NPC(s) to a random node.<br>	Arguments:   	-none-
npc_go_update_path | sv, cheat | Selected NPC(s) will go to the location that the player is looking (shown with a purple box), WITHOUT CHANGING SCHEDULE!<br>	Arguments: \[dest_fly\]
npc_kill | sv, cheat | Kills the given NPC(s)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_kill_unselected | sv, cheat | Properly kills all NPCs from the universe that aren't currently selected
npc_relationships | sv, cheat | Displays the relationships between this NPC and all others.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_reportstate | sv, cheat | Outputs the current state of the NPC
npc_reset | sv, cheat | Reloads schedules for all NPC's from their script files<br>	Arguments:	-none-
npc_route | sv, cheat | Displays the current route of the given NPC as a line on the screen.  Waypoints along the route are drawn as small cyan rectangles.  Line is color coded in the following manner:<br>	Blue	- path to a node<br>	Cyan	- detour around an object (triangulation)<br>	Red	- jump<br>	Maroon - path to final target position<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_scripted_commands | sv, cheat | Displays the state of scripted commands on the NPC<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_select | sv, cheat | Select or deselects the given NPC(s) for later manipulation.  Selected NPC's are shown surrounded by a red translucent box<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_squads | sv, cheat | Obsolete.  Replaced by npc_combat
npc_steering | sv, cheat | Displays the steering obstructions of the NPC (used to perform local avoidance)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_steering_all | sv, cheat | Displays the steering obstructions of all NPCs (used to perform local avoidance)<br>
npc_stop_moving | sv, cheat | Selected NPC(s) will stop moving.<br>	Arguments: \[asap\]
npc_task_text | sv, cheat | Outputs text debugging information to the console about the all the tasks + break conditions of the selected NPC current schedule<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_tasks | sv, cheat | Displays detailed text debugging information about the all the tasks of the selected NPC current schedule (See Overlay Text)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
npc_teleport | sv, cheat | Selected NPC will teleport to the location that the player is looking (shown with a purple box)<br>	Arguments:	-none-
npc_viewcone | sv, cheat | Displays the viewcone of the NPC (where they are currently looking and what the extents of there vision is)<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
option_duck_method | cl, a, user, per_user | Default: false<br>Input toggle control
orb_timing_debug | sv, release | Default: false<br>Spew a bunch of timing info about when orbs are hit and claimed into the log.
panorama_debugger_theme | cl, a | Default: Light<br>
panorama_focus_world_panels | cl, a | Default: false<br>when set request key focus when a world panel is enabled
panorama_joystick_enabled | a | Default: false<br>Enable panorama joystick input
particle_test_attach_attachment | sv, cheat | Default: 0<br>Attachment index for attachment mode
particle_test_attach_mode | sv, cheat | Default: follow_attachment<br>Possible Values: 'start_at_attachment', 'follow_attachment', 'start_at_origin', 'follow_origin'
particle_test_create | sv, cheat | Creates the named particle system where the player is looking.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
particle_test_destroy | sv, cheat | Destroys all particle systems matching the specified name.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
particle_test_file | sv, cheat | Default: <br>Name of the particle system to dynamically spawn
particle_test_start | sv, cheat | Dispatches the test particle system with the parameters specified in particle_test_file,<br> particle_test_attach_mode and particle_test_attach_param on the entity the player is looking at.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
particle_test_stop | sv, cheat | Stops all particle systems on the selected entities.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
password | a, norecord, server_cannot_query | Default: <br>Current server access password
pause | release | Toggle the server pause state.
pestilence_drone_healthbar_pos | cl, cheat | Default: 80<br>
phys_dynamic_scaling | sv, cl, rep, cheat | Default: true<br>
phys_expensive_shape_threshold | cl, cheat | Default: 6<br>
phys_highlight_expensive_objects | cheat | Default: false<br>Highlight expensive physics objects
phys_highlight_expensive_objects_strength | cheat | Default: 0.02<br>Highlight expensive physics objects strength
phys_joint_teleport | sv, cheat | Default: true<br>Teleport joint anchors if connected to world
phys_length_damping_ratio | sv, cheat | Default: 2<br>Spring damping ratio for length constraint
phys_length_frequency | sv, cheat | Default: 5<br>Spring stiffness for length constraint
phys_shoot | sv, cheat | Shoots a phys object.
phys_use_block_solver | sv, cheat | Default: true<br>Use block solving for constraint entities
phys_visualize_traces | sv, cl, rep, cheat | Default: false<br>
ping_quick_response | cl, release | Responds to the last ping message received
ping_wheel_phrase_0 | cl, a, per_user | Default: 1<br>
ping_wheel_phrase_1 | cl, a, per_user | Default: 2<br>
ping_wheel_phrase_2 | cl, a, per_user | Default: 4<br>
ping_wheel_phrase_3 | cl, a, per_user | Default: 34<br>
ping_wheel_phrase_4 | cl, a, per_user | Default: 18<br>
ping_wheel_phrase_5 | cl, a, per_user | Default: 5<br>
ping_wheel_phrase_6 | cl, a, per_user | Default: 42<br>
ping_wheel_phrase_7 | cl, a, per_user | Default: 6<br>
pingkeypress | cl, release | Ping keybind pressed
pixelvis_debug | cheat | Dump debug info
play | server_can_execute | Play a sound.
playcast | release | Play a broadcast
playdemo | release | Play a recorded demo file (.dem ).
player0_using_joystick | a | Default: false<br>
player_ammobalancing_debug | sv, cheat | Default: false<br>
player_debug_off_nav | sv, cheat | Default: false<br>
player_debug_print_damage | sv, cheat | Default: false<br>When true, print amount and type of all damage received by player to console.
playsoundscape | cl, cheat | Forces a soundscape to play
print_changed_convars | release | Prints all convars that have changed from their default value
private_lobby_create | cl, release | Creates a private lobby party
prop_debug | sv, cheat | Toggle prop debug mode. If on, props will show colorcoded bounding boxes. Red means ignore all damage. White means respond physically to damage but never break. Green maps health in the range of 100 down to 1.
prop_debug_collision | sv, cheat | Default: false<br>Highlights props based on their collision group: COLLISION_GROUP_PROPS(white), COLLISION_GROUP_INTERACTIVE_DEBRIS(green), COLLISION_GROUP_DEBRIS and will return to COLLISION_GROUP_INTERACTIVE_DEBRIS on sleeping(bright red), COLLISION_GROUP_DEBRIS permanently (dark red), COLLISION_GROUP_DEBRIS(blue), OTHER(grey)
prop_dynamic_create | sv, cheat | Creates a dynamic prop with a specific .vmdl aimed away from where the player is looking.<br>	Arguments: {.vmdl name}
prop_physics_create | sv, cheat | Creates a physics prop with a specific .vmdl aimed away from where the player is looking.<br>	Arguments: {.vmdl name}
pulse_debug_entity | sv, cheat | Opens a graph referencing the selected entity. If it is referenced by more than 1 graph, list all the active pulse graph instances referring to that entity so you can pick which one you want.
pulse_list_game_blackboards | sv, cheat | List all the active pulse graph instances
pulse_list_graphs | cheat | List all the active pulse graph instances
pulse_open_graph_id | cheat | Open a specific graph instance by id
pulse_print_graph_execution_history | cheat | Prints the execution history of a graph by filename or instanceid
pvs_debugentity | sv, release | Default: -1<br>Verbose spew for this entity when doing IsInPVS computation.
pvs_flowtype | sv, release | Default: 0<br>Flow through spawn groups for vis (0 == default, 1 == always visible, 2 == never visible.
pwatchent | cl, cheat | Default: -1<br>Entity to watch for prediction system changes.
pwatchvar | cl, cheat | Default: <br>Entity variable to watch in prediction system for changes.
quit | release | Quit the game
r_AirboatViewDampenDamp | sv, cl, nf, rep, cheat | Default: 1<br>
r_AirboatViewDampenFreq | sv, cl, nf, rep, cheat | Default: 7<br>
r_AirboatViewZHeight | sv, cl, nf, rep, cheat | Default: 0<br>
r_JeepViewDampenDamp | sv, cl, nf, rep, cheat | Default: 1<br>
r_JeepViewDampenFreq | sv, cl, nf, rep, cheat | Default: 7<br>
r_JeepViewZHeight | sv, cl, nf, rep, cheat | Default: 10<br>
r_citadel_cloak_blur_amount | cl, cheat | Default: 0.01<br>cloak
r_citadel_cloak_blur_factor_max_roughness | cl, cheat | Default: 1<br>cloak
r_citadel_cloak_blur_factor_min_roughness | cl, cheat | Default: 1<br>cloak
r_citadel_cloak_blur_noise_amount | cl, cheat | Default: 0.5<br>cloak
r_citadel_cloak_color_tint | cl, cheat | Default: 230 230 230 255<br>cloak
r_citadel_cloak_fresnel_effect | cl, cheat | Default: 0<br>cloak
r_citadel_cloak_intensity | cl, cheat | Default: 1<br>cloak
r_citadel_cloak_refract_amount | cl, cheat | Default: 0<br>cloak
r_citadel_cosmic_veil_fade_dist | cl, cheat | Default: 32<br>cosmic veil
r_citadel_glow_health_bar_debug | cl, cheat | Default: false<br>
r_cubemap_debug_colors | cheat | Default: 0<br>
r_debug_precipitation | cl, cheat | Default: false<br>Show precipitation volumes
r_directlighting | cheat | Default: true<br>Set to use direct lighting
r_dof_override | cheat | Default: false<br>
r_dof_override_far_blurry | cheat | Default: 2000<br>
r_dof_override_far_crisp | cheat | Default: 180<br>
r_dof_override_near_blurry | cheat | Default: -100<br>
r_dof_override_near_crisp | cheat | Default: 0<br>
r_dof_override_tilt_to_ground | cheat | Default: 0.5<br>
r_dopixelvisibility | cheat | Default: true<br>
r_draw_first_tri_only | cheat | Default: false<br>
r_draw_instances | cheat | Default: true<br>
r_draw_particle_children_with_parents | cheat | Default: -1<br>Draw particle children with parents (-1=use gameinfo, 0=no, 1=yes)
r_drawblankworld | cheat | Default: false<br>Render blank instead of the game world
r_drawdecals | cheat | Default: true<br>Set to render decals
r_drawdevvisualizers | cl, cheat | Default: false<br>Render dev visualizers
r_drawpanorama | cheat | Default: true<br>Enable the rendering of panorama UI
r_drawparticles | cheat | Default: true<br>SceneSystem/Particles/Draw Particles
r_drawropes | cl, cheat | Default: true<br>
r_drawskybox | cheat | Default: true<br>Render the 2d skybox.
r_drawtracers | cl, cheat | Default: true<br>
r_drawtracers_firstperson | cl, a, release | Default: true<br>Toggle visibility of first person weapon tracers
r_drawviewmodel | cl, cheat | Default: true<br>Render view model
r_drawworld | cheat | Default: true<br>Render the world.
r_dx11_debug_clean | release | Default: false<br>Aggressively unbind bound resources to cleanup DX11 debug warnings.
r_extra_render_frames | cheat | Default: 0<br>
r_fallback_texture_lod_scale | cheat | Default: 2<br>Scale factor for requested texture size (texture streaming) - used for geo that doesn't have a precomputed UV density measure
r_farz | cl, cheat | Default: -1<br>Override the far clipping plane. -1 means to use the value in env_fog_controller.
r_flashlightambient | cl, cheat | Default: 0<br>
r_flashlightbacktraceoffset | cl, cheat | Default: 0.4<br>
r_flashlightbrightness | cl, rep, cheat | Default: 1<br>
r_flashlightconstant | cl, rep, cheat | Default: 0<br>
r_flashlightfar | cl, rep, cheat | Default: 1500<br>
r_flashlightfov | cl, rep, cheat | Default: 53<br>
r_flashlightladderdist | cl, cheat | Default: 40<br>
r_flashlightlinear | cl, rep, cheat | Default: 100<br>
r_flashlightlockposition | cl, cheat | Default: false<br>
r_flashlightmuzzleflashfov | cl, cheat | Default: 120<br>
r_flashlightnear | cl, rep, cheat | Default: 4<br>
r_flashlightnearoffsetscale | cl, cheat | Default: 1<br>
r_flashlightoffsetforward | cl, rep, cheat | Default: 0<br>
r_flashlightoffsetright | cl, rep, cheat | Default: 5<br>
r_flashlightoffsetup | cl, rep, cheat | Default: -5<br>
r_flashlightquadratic | cl, rep, cheat | Default: 0<br>
r_flashlightshadowatten | cl, cheat | Default: 0.35<br>
r_flashlighttracedistcutoff | cl, cheat | Default: 128<br>
r_flashlighttracedistwatercutoff | cl, cheat | Default: 80<br>
r_flashlightvisualizetrace | cl, cheat | Default: false<br>
r_flush_on_pooled_ib_resize | release | Default: true<br>
r_force_no_present | cheat | Default: false<br>Force the render device to not present frames.
r_force_zprepass | cheat | Default: -1<br>0: Force z prepass off. 1: Force on. -1: Don't force
r_freezeparticles | cheat | Default: false<br>Pause particle simulation
r_fullscreen_gamma | a | Default: 2.2<br>Screen Gamma (only in fullscreen modes)
r_indirectlighting | cheat | Default: true<br>Set to use indirect lighting
r_light_probe_volume_debug_colors | cheat | Default: false<br>
r_light_probe_volume_debug_grid | cheat | Default: 0<br>Show LPV debug grid, 0: off, 1: closest only 2: closest and keep 3: all
r_light_probe_volume_debug_grid_albedo | cheat | Default: 128 128 128 255<br>albedo for LPV debug grid
r_light_probe_volume_debug_grid_bbox | cheat | Default: true<br>Show LPV bounding box when debug grid is on, 0: off, 1: on
r_light_probe_volume_debug_grid_metalness | cheat | Default: 0<br>metalness for LPV debug grid
r_light_probe_volume_debug_grid_prim | cheat | Default: 0<br>0: spheres, 1: cubes
r_light_probe_volume_debug_grid_roughness | cheat | Default: 0.5<br>roughness for LPV debug grid
r_light_probe_volume_debug_grid_samplesize | cheat | Default: 4<br>sphere radius (world) for LPV debug grid
r_lightmap_set | cheat | Default: lightmaps<br>Lightmap set to use, only works on map load
r_mapextents | cl, cheat | Default: 16384<br>Set the max dimension for the map.  This determines the far clipping plane
r_morphing_enabled | cheat | Default: true<br>
r_muzzleflashbrightness | cl, rep, cheat | Default: 0.4<br>
r_muzzleflashlinear | cl, rep, cheat | Default: 0.05<br>
r_nearz | cl, cheat | Default: -1<br>Override the near clipping plane. -1 means use the default.
r_particle_max_draw_distance | cheat | Default: 1e+06<br>The maximum distance that particles will render
r_particle_multiplier | cheat | Default: 1<br>Render each particle system N times for perf testing
r_pixelvisibility_partial | cheat | Default: true<br>
r_pixelvisibility_spew | cheat | Default: false<br>
r_render_world_node_bounds | cheat | Default: false<br>Render world node bounds
r_rendersun | cheat | Default: true<br>Render sun lighting
r_replay_post_effect | cl, cheat | Default: -1<br>
r_shadows | cheat | Default: true<br>
r_shadowtile_waveops |  | Default: false<br>
r_showdebugoverlays | cheat | Default: false<br>Set to render debug overlays
r_showdebugrendertarget | cheat | Default: false<br>Set the debug render target to show, 0 == disable
r_showsceneobjectbounds | cheat | Default: false<br>Show scenesystem object bounding boxes
r_showsunshadowdebugrendertargets | cheat | Default: false<br>Set to render sun shadow render targets
r_showsunshadowdebugsplitvis | cheat | Default: false<br>Set to render sun shadow split visibility debugger
r_size_cull_threshold_shadow | cheat | Default: 0.2<br>Threshold of shadow map size percentage below which objects get culled
r_skinning_enabled | cheat | Default: true<br>
r_smooth_morph_normals | release | Default: true<br>
r_texture_lod_scale | cheat | Default: 1<br>Scale factor for requested texture size (texture streaming)
r_translucent | cheat | Default: true<br>Enable rendering of translucent geometry
r_zprepass_normals | cheat | Default: false<br>0: Use normals reconstructed from depth. 1: Output correct normals in z prepass.
ragdoll_biped_settle_duration | sv, cheat | Default: 1.5<br>
ragdoll_biped_settle_force | sv, cheat | Default: 0.5<br>
ragdoll_biped_settle_lift_force | sv, cheat | Default: 0.2<br>
ragdoll_biped_settle_start_time | sv, cheat | Default: 0.5<br>
ragdoll_biped_settle_vertical_limit | sv, cheat | Default: 0.7<br>
ragdoll_cleanup_all | sv, cl, cheat | Cleans up all ragdolls.
ragdoll_lru_debug_removal | sv, cl, rep, cheat | Default: false<br>
ragdoll_lru_min_age | sv, cl, rep, cheat | Default: 10<br>
ragdoll_move_entity | sv, cl, rep, cheat | Default: false<br>
ragdoll_resolve_initial_conflict | sv, cl, rep, cheat | Default: false<br>
ragdoll_resolve_separation | sv, cl, rep, cheat | Default: false<br>
ragdoll_update_from_weights | sv, cl, rep, cheat | Default: false<br>
rangefinder | sv, cheat | Measures distance along a ray
rangefinder2d | sv, cheat | Measures distance along a ray, only measuring along XY plane.
rate | a, user | Default: 786432<br>Min bytes/sec the host can receive data
rcon | norecord, release | Issue an rcon command.
rcon_address | norecord, release, server_cannot_query | Default: <br>Address of remote server if sending unconnected rcon commands (format x.x.x.x:p)
rcon_connected_clients_allow | rep, release | Default: true<br>Allow clients to use rcon commands on server.
rcon_password | norecord, release, server_cannot_query | Default: <br>remote console password.
recast_mark_overhang | sv, rep, cheat | Default: false<br>Enable/disable overhang detection
recast_partitioning | sv, rep, cheat | Default: 0<br>0 = watershed, 1 = monotone, 2 = layers
record | cheat, norecord, release | Record a demo.
reloadgame | cheat | Reload the most recent saved game.
remove_weapon | sv, cheat | Remove a weapon held by the player.<br>	Arguments: &lt;weapon subclass name&gt;
repeat_last_console_command | release | Repeat last console command.
replay_death | sv, cheat | start hltv replay of last death
replay_debug | rep, release | Default: 0<br>
replay_start | sv, cheat | Start Source2 TV replay: replay_start &lt;delay&gt;\|stash \[&lt;player name or index&gt;\]
replay_stop | sv | stop hltv replay
report_cliententitysim | cl, cheat | Default: false<br>List all clientside simulations and time - will report and turn itself off.
report_clientthinklist | cl, cheat | Default: false<br>List all clientside entities thinking and time - will report and turn itself off.
reset_camera | cl, release | Pitch the camera back toward the horizon over time. Use citadel_reset_camera_duration_ms to tweak the speed.
reset_gameconvars | cheat | Reset game convars to default values
reset_voice_on_input_stallout | user | Default: false<br>If true, resets the input device when there was a long enough hitch between callbacks.
respawn_player | sv, cheat | Respawns the player from death!<br>
restart | cheat | Poor man's restart: reload the current map from disk.
rr_dump_rules | sv, cheat | Print all response rules
rr_followup_maxdist | sv, cheat | Default: 1800<br>'then ANY' or 'then ALL' response followups will be dispatched only to characters within this distance.
rr_forceconcept | sv, cheat | fire a response concept directly at a given character.<br>USAGE: rr_forceconcept &lt;target name or index&gt; &lt;concept&gt; "criteria1:value1,criteria2:value2,..."<br>criteria values are optional.<br>
rr_reloadresponsesystems | sv, cheat | Reload all response system scripts.
rr_thenany_score_slop | sv, a, cheat | Default: 0<br>When computing respondents for a 'THEN ANY' rule, all rule-matching scores within this much of the best score will be considered.
run_perftest | cheat, norecord | Execute perftest.cfg
save_animgraph_recording | sv, cheat | Saves all active animgraph recordings to disk<br>	Arguments: automaticallyOpenInAnimgraphEditor
save_maxarray_spew | sv, release | Default: 10<br>Max number of array entries to spew when using SaveRestoreIO spewing.
say | sv | Display player message
say_chat | cl, release | Opens chat menu to chat with everyone
say_chat_team | cl, release | Opens chat menu to chat with Allies
say_team | sv | Display player message to team
sc_aggregate_indirect_draw_compaction | release | Default: true<br>Use multidrawindirect...count if the driver/hardware supports it
sc_aggregate_indirect_draw_compaction_threshold | release | Default: 8<br>Threshold of indirect draws when we will do compaction
sc_disableThreading | cheat | Default: false<br>
sc_disable_culling_boxes | cheat | Default: false<br>
sc_disable_procedural_layer_rendering | cheat | Default: false<br>
sc_disable_shadow_fastpath | cheat | Default: false<br>
sc_disable_spotlight_shadows | cheat | Default: false<br>
sc_disable_world_materials | cheat | Default: false<br>
sc_dump_lists | cheat | Default: <br>
sc_dumpworld | cheat | Dump a list of the objects in a sceneworld (Usage: sc_dumpworld &lt;world_index&gt;)
sc_dumpworld3d | cheat | Dump the objects in a sceneworld into a 3d geoview buffer (Usage: sc_dumpworld3d &lt;world_index&gt;)
sc_extended_stats | cheat | Default: false<br>
sc_fade_distance_scale_override | cheat | Default: -1<br>
sc_force_lod_level | cheat | Default: -1<br>
sc_force_materials_batchable | cheat | Default: false<br>
sc_force_translation_in_projection | cheat | Default: false<br>If enabled, the camera's translation will be included in the projection matrix.
sc_listworlds | cheat | List all the active sceneworlds
sc_only_render_opaque | cheat | Default: false<br>
sc_only_render_shadowcasters | cheat | Default: false<br>
sc_reject_all_objects | cheat | Default: false<br>
sc_screen_size_lod_scale_override | cheat | Default: -1<br>
sc_setclassflags | cheat | Low level command to set the flags byte associated with an object class. sc_SetClassFlags &lt;classname&gt; &lt;value&gt;<br>
sc_showclasses | cheat | List the object class names known by scenesystem<br>
sc_skip_traversal | cheat | Default: false<br>
scale_function_dump | sv, cheat | Print out all scale functions.
scene_playvcd | sv, cheat | Play the given VCD as an instanced scripted scene.
scene_showfaceto | sv, a, cheat | Default: false<br>When playing back, show the directions of faceto events.
scene_showmoveto | sv, a | Default: false<br>When moving, show the end location.
screenmessage_show | cheat | Default: -1<br>Enable display of console messages on screen. 1 = Enabled, 0 = Disabled, -1 = Enabled if vgui is not present
script_add_debug_filter | sv, cheat | Add a filter to the game debug overlay
script_add_watch | sv, cheat | Add a watch to the game debug overlay
script_add_watch_pattern | sv, cheat | Add a watch to the game debug overlay
script_attach_debugger | sv, cheat | Connect the vscript VM to the script debugger
script_clear_watches | sv, cheat | Clear all watches from the game debug overlay
script_debug | sv, cheat | Toggle the in-game script debug features
script_dump_all | sv, cheat | Dump the state of the VM to the console
script_find | sv, cheat | Find a key in the VM
script_help | sv, cheat | Output help for script functions
script_reload | sv, cheat | Reload scripts
script_reload_code | sv, cheat | Execute a vscript file, replacing existing functions with the functions in the run script
script_reload_entity_code | sv, cheat | Execute all of this entity's VScripts, replacing existing functions with the functions in the run scripts
script_remove_debug_filter | sv, cheat | Remove a filter from the game debug overlay
script_remove_watch | sv, cheat | Remove a watch from the game debug overlay
script_remove_watch_pattern | sv, cheat | Remove a watch from the game debug overlay
script_resurrect_unreachable | sv, cheat | Use the garbage collector to track down reference cycles
script_trace_disable | sv, cheat | Turn off a particular trace output by file or function name
script_trace_disable_all | sv, cheat | Turn off all trace output
script_trace_disable_key | sv, cheat | Turn off a particular trace output by table/instance
script_trace_enable | sv, cheat | Turn on a particular trace output by file or function name
script_trace_enable_all | sv, cheat | Turn on all trace output
script_trace_enable_key | sv, cheat | Turn on a particular trace output by table/instance
sdr | release | An old command that has been renamed to 'net_option'
sensitivity | cl, a, user, per_user | Default: 1.25<br>Mouse sensitivity.
sensitivity_y_scale | cl, a, user, per_user | Default: 1<br>Multiplies the mouse Y axis for finer pitch vs yaw aim
servercfgfile | sv, release | Default: server.cfg<br>
setang | sv, cheat | Snap player eyes to specified pitch yaw &lt;roll:optional&gt; (must have sv_cheats).
setang_exact | sv, cheat | Snap player eyes and orientation to specified pitch yaw &lt;roll:optional&gt; (must have sv_cheats).
setinfo | clientcmd_can_execute | Adds a new user info value
setmodel | sv, cheat | Changes's player's model
setpause | release | Set the pause state of the server.
setpos | sv, cheat | Move player to specified origin (must have sv_cheats).
setpos_exact | sv, cheat | Move player to an exact specified origin (must have sv_cheats).
setpos_player | sv, cheat | Move specified player to specified origin (must have sv_cheats).
shake | sv, cheat | Shake the screen.
shake_stop | cl, cheat | Stops all active screen shakes.<br>
shake_testpunch | cl, cheat | Test a punch-style screen shake.<br>
shatterglass_break | sv, cheat | 
shatterglass_cleanup | sv, cl, rep, cheat | Default: true<br>
shatterglass_cleanup_max | sv, cl, rep, cheat | Default: 200<br>
shatterglass_debug | sv, cl, rep, cheat | Default: false<br>
shatterglass_hit_tolerance | sv, cl, rep, cheat | Default: 2<br>
shatterglass_restore | sv, cheat | 
shatterglass_shard_lifetime | sv, cl, rep, cheat | Default: 15<br>
show_steam_id | cl, release | Prints out the local user's Steam ID. Handy for getting account ID for a player
show_visibility_boxes | cl, cheat | Default: false<br>Enable or Disable debug display of visibility boxes
showconsole | norecord, release | Show the console.
showents | sv, cheat | Dump entity list to console.
showtriggers | sv, cheat | Enable or Disable showing trigger entities
showtriggers_toggle | sv, cheat | Displays the movement bounding box for the triggers in orange.  Some entites will also display entity specific overlays.<br>	Arguments:   	{entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
silence_dsp | cheat | Default: false<br>When on, silences all DSP mixes.
sk_autoaim_mode | sv, cl, a, rep | Default: 1<br>
skel_constraints_enable | rep, cheat | Default: true<br>
skeleton_instance_scaleset_enable | sv, cl, rep, cheat | Default: true<br>
skeleton_instance_smear_boneflags | sv, cheat | Default: false<br>Smear boneflags across the model.  Costs computation, but tests to make sure your bone flags are consistent.
skill | sv, cl, a, rep, per_user | Default: 1<br>Game skill level.
snd_arrangement_start | cheat | Starts the specified arrangement.
snd_autodetect_latency | a | Default: true<br>
snd_break_on_start_soundevent | sv, cl, rep, cheat | Default: <br>Use to debug break on any soundevent that is started matching this name
snd_cast | cheat | Casts a ray and starts a sound event where the ray hits. The sound event will retrigger periodically if cl_snd_cast_retrigger is set. The sound event will clear previous snd_cast events if cl_snd_cast_clear is set. Usage: snd_cast &lt;eventname&gt; \[&lt;retrigger time&gt;\] \[&lt;max distance&gt;\]. Arguments that are specified will become defaults for the remainder of the session.
snd_disable_mixer_duck | cheat | Default: false<br>
snd_disable_mixer_solo | cheat | Default: false<br>
snd_dsp_distance_max | cheat | Default: 2000<br>
snd_dsp_distance_min | cheat | Default: 20<br>
snd_duckerattacktime | a | Default: 0.5<br>
snd_duckerreleasetime | a | Default: 2.5<br>
snd_duckerthreshold | a | Default: 0.15<br>
snd_ducktovolume | a | Default: 0.55<br>
snd_envelope_rate | cheat | Default: 100<br>
snd_filter | cheat | Default: <br>
snd_foliage_db_loss | sv, cheat | Default: 4<br>foliage dB loss per 1200 units
snd_gain | a | Default: 1<br>
snd_gain_max | cheat | Default: 1<br>
snd_gain_min | cheat | Default: 0.01<br>
snd_gamevoicevolume | a | Default: 1<br>Game v.o. volume
snd_gamevolume | a | Default: 1<br>Game volume
snd_get_physics_surface_properties | cheat | Get physics surface properties for all the materials.
snd_group_cluster_debug | rep, cheat | Default: false<br>
snd_group_priority_debug | rep, cheat | Default: false<br>
snd_group_priority_max_tolerance | rep, cheat | Default: 0.05<br>
snd_list | cheat | Default: <br>
snd_log_empty_event_entities | cl, cheat | Default: false<br>Logs the sound event entities that have empty names.
snd_mixahead | a | Default: 0.001<br>
snd_mixer_master_dsp | cheat | Default: 1<br>
snd_mixer_master_level | cheat | Default: 1<br>
snd_musicvolume | a | Default: 1<br>Music volume
snd_mute_losefocus | a | Default: true<br>
snd_new_visualize | sv, cheat | Default: false<br>Displays soundevent name played at it's 3d position
snd_occlusion_bounces | rep, cheat | Default: 1<br>
snd_occlusion_debug | sv, cl, rep, cheat | Default: false<br>
snd_occlusion_min_wall_thickness | rep, cheat | Default: 4<br>
snd_occlusion_rays | rep, cheat | Default: 4<br>
snd_op_test_convar | cheat | Default: 720<br>
snd_opvar_set_point_debug | sv, cl, rep, cheat | Default: false<br>
snd_print_activetracks | cheat | List all active tracks
snd_print_arrangements | cheat | List all available sequence arrangments
snd_print_samplers | cheat | List all available samplers
snd_print_sequences | cheat | List all available midi sequences
snd_rear_stereo_scale | rep, cheat | Default: 1<br>
snd_refdb | cheat | Default: 60<br>Reference dB at snd_refdist
snd_refdist | cheat | Default: 36<br>Reference distance for snd_refdb
snd_report_audio_nan | release | Default: true<br>
snd_report_verbose_error | cheat | Default: false<br>If set to 1, report more error found when playing sounds.<br>
snd_samplers_play_note | cheat | Play a note from a specified sampler
snd_samplers_stop_note | cheat | Stop a note from a specified sampler
snd_sequence_set_track_bpm | cheat | Sets the tempo of the specified track
snd_sequence_set_track_transpose | cheat | Sets the transposition of the specified track
snd_sequence_stop_all_tracks | cheat | Stops all currently playing sequences
snd_sequence_stop_track | cheat | Stops the specified track
snd_sequencer_show_bpm | cheat | Default: false<br>
snd_sequencer_show_events | cheat | Default: false<br>
snd_sequencer_show_quantize_queue | cheat | Default: false<br>
snd_set_physics_surface_properties | cheat | Set physics surface properties for materials. Usage: &lt;heuristic #&gt; &lt;commit&gt;
snd_showclassname | cheat | Default: 0<br>
snd_showstart | cheat | Default: 0<br>
snd_sos_block_global_stack | cheat | Default: false<br>
snd_sos_block_stop_global_stack | cheat | Default: true<br>
snd_sos_calc_angle_debug | rep, cheat | Default: false<br>
snd_sos_compare_operator_stacks | cheat | Compares 2 operator stacks and spews any errors
snd_sos_flush_operators | cheat | Flush and re-parse the sound operator system
snd_sos_get_operator_field_info | cheat | Currently gets info for a single operator field
snd_sos_ingame_debug | cheat | Default: false<br>
snd_sos_list_operator_updates | cheat | Default: false<br>
snd_sos_opvar_debug | cheat | Default: false<br>
snd_sos_pause_soundevent | cheat | Pause the specified soundevent in the list
snd_sos_pause_system | cheat | Default: false<br>
snd_sos_print_addfield_dupes | cheat | Default: false<br>
snd_sos_print_class_sizes | cheat | Prints the sizes of relevant sos classes.
snd_sos_print_field_name_strings | cheat | Prints a list of currently cached field name strings
snd_sos_print_field_references | cheat | Default: false<br>
snd_sos_print_fps | cheat | Default: false<br>
snd_sos_print_full_field_info | cheat | Default: false<br>
snd_sos_print_groups | cheat | Prints the current state of the groups system
snd_sos_print_operator_stack | cheat | Prints a master list of currently exposed variables
snd_sos_print_operator_stack_operator | cheat | Prints an operator from a stack
snd_sos_print_operator_stacks | cheat | Prints a list of currently available stacks
snd_sos_print_operators | cheat | Prints a list of currently available operators
snd_sos_print_stack_exec_list | cheat | Prints the current stack execution list
snd_sos_print_strings | cheat | Prints a list of currently cached strings
snd_sos_print_table_arrays | cheat | Default: false<br>
snd_sos_print_tool_properties | cheat | Prints the current state of tool properties.
snd_sos_resolve_execute_operator | cheat | Resolve the inputs and execute one specified operator from a specified stack
snd_sos_set_operator_field | cheat | Currently sets a single float operator field
snd_sos_set_operator_field_by_guid | cheat | Currently sets a single float operator field
snd_sos_show_block_debug | cheat | Default: false<br>Spew data about the list of block entries.
snd_sos_show_operator_event_and_stack | cheat | Default: true<br>
snd_sos_show_operator_event_filter | cheat | Default: <br>
snd_sos_show_operator_field_filter | cheat | Default: <br>
snd_sos_show_operator_init | cheat | Default: false<br>
snd_sos_show_operator_not_executing | cheat | Default: true<br>
snd_sos_show_operator_operator_filter | cheat | Default: <br>
snd_sos_show_operator_pause_entry | cheat | Default: false<br>
snd_sos_show_operator_shutdown | cheat | Default: false<br>
snd_sos_show_operator_stop_entry | cheat | Default: false<br>
snd_sos_show_operator_updates | cheat | Default: false<br>
snd_sos_show_opfield_cache_updates | cheat | Default: false<br>
snd_sos_show_opvar_updates | cheat | Default: false<br>
snd_sos_show_opvar_updates_filter | cheat | Default: <br>
snd_sos_show_queuetotrack | cheat | Default: false<br>
snd_sos_show_soundevent_param_overwrite | cheat | Default: false<br>
snd_sos_show_soundevent_start | cheat | Default: false<br>
snd_sos_soundevent_filter | cheat | Default: <br>
snd_sos_soundevent_profile | cheat | Dump a record of current soundevents and profile data
snd_sos_start_soundevent | cheat | Starts a specified soundevent
snd_sos_start_soundevent_at_pos | cheat | Starts a specified soundevent at the given position
snd_sos_start_stack | cheat | Starts a specified stack via an empty soundevent
snd_sos_stop_all_soundevents | cheat | Stops all soundevents currently on the execution list
snd_sos_stop_soundevent_guid | cheat | Stops a specified soundevent
snd_sos_stop_soundevent_index | cheat | Stops a specified soundevent
snd_sos_stop_track | cheat | Stop the specified track and it's queue.
snd_sos_test_soundmessage | cheat | test
snd_sos_unpause_soundevent | cheat | UnPause the first soundevent in the list
snd_sound_areas_debug | cl, rep, cheat | Default: false<br>
snd_sound_areas_debug_interval | cl, rep, cheat | Default: 0.2<br>
snd_soundmixer_update_maximum_frame_rate | cheat | Default: 0<br>
snd_spatialize_lerp | a, release | Default: 0<br>
snd_steamaudio_baked_data_stats | cheat | Display baked data stats for the current mod.
snd_steamaudio_baked_occlusion_mode | cheat | Default: 0<br>0: distance ratio only. 1: deviation only (1/r). 2: deviation only (linear). 3: Mode 0 and Mode 1, 4: Mode 0 and Mode 2
snd_steamaudio_enable_pathing | cheat | Default: false<br>This variable is checked by soundstack to globally enabling pathing for audio processing.
snd_steamaudio_enable_perspective_correction | a, release | Default: false<br>Enable perspective correction for 3D audio.
snd_steamaudio_enable_reverb | release | Default: 0<br>Enable Steam Audio Reverb processor.
snd_steamaudio_enable_spatial_blend_fix | cheat | Toggles the speculative fix for low-frequency issues when using spatial blend.
snd_steamaudio_halton_sequence | cheat | Generate Halton Sequence for a given order and number of samples.
snd_steamaudio_ir_duration | cheat | Default: 1<br>The time delay between a sound being emitted and the last audible reflection in Steam Audio.
snd_steamaudio_max_convolution_sources | cheat | Default: 4<br>The maximum number of simultaneous sources that can be modeled by Steam Audio.
snd_steamaudio_max_occlusion_samples | cheat | Default: 64<br>The maximum number of rays that can be traced for volumetric occlusion by Steam Audio.
snd_steamaudio_num_bounces | cheat | Default: 128<br>The maximum number of times any ray can bounce when using Steam Audio.
snd_steamaudio_num_diffuse_samples | cheat | Default: 2048<br>The number of directions considered for ray bounce by Steam Audio.
snd_steamaudio_num_rays | cheat | Default: 65536<br>The number of rays to trace for reflection modeling by Steam Audio.
snd_steamaudio_num_threads | cheat | Default: 2<br>Sets the number of threads used for realtime reflection by Steam Audio.
snd_steamaudio_pathing_order | cheat | Default: 1<br>The amount of directional detail in the simulated by Steam Audio.
snd_steamaudio_pathing_order_rendering | cheat | Default: 1<br>The amount of directional detail in the rendered audio by Steam Audio.
snd_steamaudio_reverb_level_db | release | Default: -3<br>Adjust overall volume (dB) of the output from Steam Audio Reverb processor.
snd_steamaudio_source_pathing_debug | a | Default: false<br>Enable path visualization for steam_audio_source operator.
snd_toolvolume | a | Default: 1<br>Volume of sounds in tools (e.g. Hammer, SFM)
snd_use_baked_occlusion | rep, cheat, release | Default: 0<br>
snd_vmidi_flush | cheat | Purge and reload all vmidi data and files.
snd_vmix_override_mix_decay_time | cheat | Default: -1<br>If set &gt; 0, overrides how long the decay time is on all mix graphs (in seconds).<br>
snd_vmix_show_input_updates | cheat | Default: false<br>If set to 1, show all incoming updates to vmix inputs.<br>
snd_voipvolume | a | Default: 1<br>Voice volume
sound_device_override | a, release | Default: <br>ID of the sound device to use
soundinfo | release | Describe the current sound device with an active voice list.
soundscape_debug | sv, cheat | Default: false<br>When on, draws lines to all env_soundscape entities. Green lines show the active soundscape, red lines show soundscapes that aren't in range, and white lines show soundscapes that are in range, but not the active soundscape.
soundscape_dumpclient | cl, cheat | Dumps the client's soundscape data.<br>
soundscape_fadetime | cl, cheat | Default: 3<br>Time to crossfade sound effects between soundscapes
soundscape_radius_debug | cl, cheat | Default: false<br>Prints current volume of radius sounds
spawn_group_activate | sv, cheat | Activate specified spawngroup.
spawn_group_load | sv, cheat | Load named spawn group.
spawn_group_unload | sv, cheat | Unload named spawn group.
spawn_hero_testing_controller | sv, release | Spawns an entity that activates sandbox mode controls.
speaker_config | a | Default: 0<br>
spec_autodirector | cl, clientcmd_can_execute | Default: true<br>Auto-director chooses best view modes while spectating
spec_centerchasecam | cl, a | Default: false<br>Looks at the target player's center, instead of his eye position, in chase came mode
spec_chase | cl, release | Changes the spectate mode to chase
spec_goto | cl, release | Changes the spectate mode to roaming and go to the location
spec_in_eye | cl, release | Changes the spectate mode to in-eye
spec_mode | cl, clientcmd_can_execute | Set spectator mode
spec_next | cl, clientcmd_can_execute | Spectate next player
spec_player | cl, clientcmd_can_execute | Spectate a player by name or slot
spec_pos | cl, cheat | dump position and angles to the console
spec_prev | cl, clientcmd_can_execute | Spectate previous player
spec_replay_autostart | cl, a | Default: true<br>Auto-start Killer Replay when available
spec_replay_bot | sv, release | Default: false<br>Enable Spectator Hltv Replay when killed by bot
spec_replay_enable | rep, release | Default: 0<br>Enable Killer Replay, requires hltv server running (0:off, 1:default, 2:force)
spec_replay_leadup_time | rep, release | Default: 5.3438<br>Replay time in seconds before the highlighted event
spec_replay_message_time | rep, release | Default: 9.5<br>How long to show the message about Killer Replay after death. The best setting is a bit shorter than spec_replay_autostart_delay + spec_replay_leadup_time + spec_replay_winddown_time
spec_replay_on_death | rep, release | Default: false<br>When &gt; 0, sets the mode whereas players see delayed replay, and are segregated into a domain of chat and voice separate from the alive players
spec_replay_rate_base | rep, release | Default: 1<br>Base time scale of Killer Replay.Experimental.
spec_replay_rate_limit | rep, release | Default: 3<br>Minimum allowable pause between replay requests in seconds
spec_replay_winddown_time | sv, release | Default: 2<br>The trailing time, in seconds, of replay past the event, including fade-out
spec_target | cl, release | Changes the target being spectated
splitscreen_mode | a, cheat | Default: 0<br>
startdemos | release | Play demos in demo sequence.
status | release | Print connection status
status_json | release | Print status in JSON format
steam_inputhandler_glyph_lock_mode | cl, a, release | Default: 0<br>0: Automatic (Default) - switch glyphs when a keyboard bind or controller bind activates. 1: Keyboard and Mouse only. 2: Controller Only
steaminput_glyph_use_universal_face_buttons | cl, a, release | Default: true<br>When enabled, Face Buttons use a diamond of circles, rather than controller specific glyphs for faces
stop | release | Finish recording demo.
stopdemos | release | Stop looping demos (current demo will complete).
stopsound | cheat | 
stopsoundscape | cl, cheat | Stops all soundscape processing and fades current looping sounds
subclass_change | sv, cheat | Changes the subclass of the given entity.<br>	Arguments:   	&lt;new_subclass&gt; {entity_name} / {class_name} / {entity_index} / {no argument = pick what player is looking at}
subclass_create | sv, cheat | Creates an entity of the given subclass where the player is looking.
surfaceprop | sv, cheat | Reports the surface properties at the cursor
survey_chance | cl, release | Default: 0<br>Percentage chance of showing the survey questions when entering matchmaking
survey_min_games_played | cl, release | Default: 10<br>Don't allow for showing the survey unless a minimum number of games have been played
sv_accelerate | sv, cl, nf, rep, release | Default: 10<br>
sv_airaccelerate | sv, cl, nf, rep, release | Default: 10<br>
sv_allchat | sv, nf, release | Default: true<br>Players can receive all other players' text chat, no death restrictions
sv_alltalk | sv, nf, release | Default: false<br>Players can hear all other players' voice communication, no team restrictions
sv_audio_debug_bullet_material | sv, cheat | Default: false<br>Visualize bullet material info.
sv_audio_debug_pawn_surface_data | sv, cheat | Default: false<br>Visualize pawn surface data.
sv_audio_log_participant_start_messages | sv, cheat | Default: false<br>Prints when a participant sound message was sent.
sv_banid_enabled | release | Default: true<br>Whether server supports banid command
sv_bounce | sv, cl, nf, rep, release | Default: 0<br>Bounce multiplier for when physically simulated objects collide with other objects.
sv_bullet_travel_debug_path | sv, cheat | Default: 0<br>Debug: visualization time for lazily calculated bullet paths (0 = disable)
sv_bullet_travel_debug_trace | sv, cheat | Default: 0<br>Debug: visualization time for active bullet traces (0 = disable)
sv_cheats | nf, rep, release | Default: false<br>Allow cheats on server
sv_citadel_bebop_beam_draw_points | sv, cheat | Default: false<br>
sv_citadel_log_ability_use | sv, release | Default: false<br>
sv_clockcorrection_msecs | sv, release | Default: 60<br>The server tries to keep each player's m_nTickBase withing this many msecs of the server absolute tickcount
sv_cluster | release | Default: 0<br>Data center cluster this server lives in.
sv_cq_trim_bloat_remainder | sv, release | Default: 1<br>When trimming a bloated CQ, leave at least N more commands than the minimum
sv_cq_trim_bloat_space | sv, release | Default: 0<br>When trimming a bloated CQ, try to leave room for N more commands to be added.  0 will trim only what is needed to remove the immediate bloat, a very large value will reset the whole queue.
sv_cq_trim_catchup_remainder | sv, release | Default: 1<br>When trimming an overful CQ due to app 'catchup' request, leave at least N more commands than the minimum
sv_crash_sentinel_filename | sv, release | Default: <br>Filename of crash detection sentinel
sv_debug_client_not_in_pvs | sv, cheat | Default: false<br>If set, draw failed client PVS checks with red box
sv_debug_overlays_bandwidth | release | Default: 65536<br>Broadcast server debug overlays traffic
sv_debug_overlays_broadcast | nf, cheat, release | Default: false<br>Broadcast server debug overlays
sv_deltaticks_enforce | release | Default: 2<br>By default, player must ack delta ticks in order. How to enforce it: 2 = kick all clients, 1 = kick only TV clients, 0 = do not kick.
sv_deltaticks_log | release | Default: 2<br>Whether diagnostic logging is enabled when clients ack delta ticks out of order. Policy: 2 = log all out of order acks, 1 = log only when disconnect is triggered, 0 = do not log.
sv_enable_alternate_baselines | release | Default: 1<br>Allow alternate baseline system, set to 2 for debugging spew.
sv_enable_delta_packing | release | Default: true<br>When enabled, this allows for entity packing to use the property changes for building up the data. This is many times faster, but can be disabled for error checking.
sv_enable_hideout | sv, rep, release | Default: true<br>When registering for MM, we can be assigned hideouts
sv_enable_match | sv, rep, release | Default: true<br>When registering for MM, we can be assigned normal matches
sv_enable_removearrayelementsoutsidemetadatabounds | release | Default: false<br>
sv_ent_showonlyhitbox | sv, cheat | Default: -1<br>
sv_ents_write_alarm | release | Default: 0<br>Print callstack every time CNetworkGameServerBase::WriteEntityUpdate takes more than this amount of milliseconds
sv_friction | sv, cl, nf, rep, release | Default: 4<br>World friction.
sv_gameinstructor_disable | cl, rep, release | Default: false<br>Force all clients to disable their game instructors.
sv_gameinstructor_enable | cl, rep, release | Default: false<br>Force all clients to enable their game instructors.
sv_gravity | sv, cl, nf, rep, release | Default: 800<br>World gravity.
sv_hibernate_postgame_delay | release | Default: 5<br># of seconds to wait after final client leaves before hibernating.
sv_hibernate_when_empty | release | Default: true<br>Puts the server into extremely low CPU usage mode when no clients connected
sv_hoststate_quit_syscall | release | Default: false<br>When enabled, game server will quit immediately via syscall instead of running host states shutdown sequence
sv_infinite_ammo | sv, cl, rep, cheat, release | Default: 0<br>Player's active weapon will never run out of ammo
sv_ladder_slack_z_mult | sv, cl, rep, cheat | Default: 0.026<br>Difference in Z increases toward the middle of the slack ladder.<br>
sv_lagcomp_filterbyviewangle | sv, cheat | Default: false<br>If true, player pawn will filter lag compensation targets by their view angle.
sv_lagcompensationforcerestore | sv, cheat | Default: true<br>Don't test validity of a lag comp restore, just do it.
sv_lan | release | Default: false<br>Server is a lan server ( no heartbeat, no authentication, no non-class C addresses )
sv_late_commands_allowed | sv, release | Default: 5<br>Allow N late commands to run at 0 timescale prior to running an on-time command. Negative values for network round trip based calculation with a hard cap of the of absolute value
sv_lightquery_debug | sv, cheat | Default: false<br>
sv_listen_directudp | release | Default: true<br>Server will listen for direct UDP connections on the configured port.  This can be turned off to only listen for P2P/SDR connections.
sv_log_onefile | a, release | Default: false<br>Log server information to only one file.
sv_logbans | a, release | Default: false<br>Log server bans in the server logs.
sv_logblocks | release | Default: false<br>If true when log when a query is blocked (can cause very large log files)
sv_logecho | a, release | Default: true<br>Echo log information to the console.
sv_logfile | a, release | Default: false<br>Log server information in the log file.
sv_logflush | a, release | Default: false<br>Flush the log file to disk on each write (slow).
sv_logsdir | a, release | Default: logs<br>Folder in the game directory where server logs will be stored.
sv_matchmaking_enabled | sv, rep, release | Default: false<br>Register with the GC for matchmaking
sv_matchperfstats_send_to_steam | sv, release | Default: true<br>Set to false to disable sending match perf stats to steam
sv_max_queries_sec | release | Default: 3<br>Maximum queries per second to respond to from a single IP address.
sv_max_queries_sec_global | release | Default: 60<br>Maximum queries per second to respond to from anywhere.
sv_max_queries_window | release | Default: 30<br>Window over which to average queries per second averages.
sv_maxrate | rep, release | Default: 0<br>Max bandwidth rate allowed on server, 0 == unlimited
sv_maxspeed | sv, cl, nf, rep, release | Default: 320<br>
sv_maxunlag | sv, release | Default: 0.5<br>Maximum lag compensation in seconds
sv_maxunlag_player | sv, release | Default: 0.2<br>If &gt;0, maximumum lag compensation used for other human pawns. Applied after sv_maxunlag!
sv_maxupdaterate | sv, cl, rep, release | Default: 60<br>Maximum updates per second that the server will allow
sv_maxvelocity | sv, cl, rep, release | Default: 3500<br>Maximum speed any ballistically moving object is allowed to attain per axis.
sv_memlimit | cheat, release | Default: 0<br>If set, whenever a game ends, if the total memory used by the server is greater than this # of megabytes, the server will exit.
sv_merge_changes_after_tick_with_calcdelta | release | Default: 1<br>This fixes bugs where pure calcdelta is used due to recipient changing but it doesn't pick up a field change where the value was changed back to same value as the from snapshot even though the destination fields change list does note the change. Set to 2 to spew any changes merged in by this fix.
sv_metaduplication | cheat | Check serializer meta for duplication, add verbose to command for full spew
sv_minrate | rep, release | Default: 98304<br>Min bandwidth rate allowed on server, 0 == unlimited
sv_minupdaterate | sv, cl, rep, release | Default: 10<br>Minimum updates per second that the server will allow
sv_networkvar_perfieldtracking | release | Default: true<br>Track individual field offset changes, rather than a single dirty flag for the whole entity.
sv_networkvar_validate | release | Default: false<br>Validate each StateChanged against known offsets.
sv_noclipaccelerate | sv, cl, a, nf, rep | Default: 5<br>
sv_noclipduringpause | sv, cl, rep, cheat | Default: false<br>If cheats are enabled, then you can noclip with the game paused (for doing screenshots, etc.).
sv_noclipfriction | sv, cl, a, nf, rep | Default: 4<br>Friction during noclip move.
sv_noclipspeed | sv, cl, a, nf, rep | Default: 1200<br>
sv_packstats | release | Show entity packing stats, pass 'clear' as argument to reset counts.
sv_parallel_checktransmit | sv, release | Default: 0<br>Set to 1 to use threaded checkentities for transmit/pvs on listen servers, 2 for dedicated servers.
sv_parallel_packentities | release | Default: 2<br>Set to 1 to use threaded snapshot sending on listen servers, 2 for dedicated servers.
sv_parallel_sendsnapshot | release | Default: 2<br>0: run all send jobs on main thread; 1: send jobs run asynchronously (except on dedicated server); 2: send jobs asynchronously; 3: send jobs run in parallel but block to not overlap the next tick; 4: main server clients' send jobs run in parallel, then HLTV server jobs; this approximately matches pre-async profile for a single HLTV server configuration
sv_password | prot, nf, norecord, release | Default: <br>Server password for entry into multiplayer games
sv_pausable | release | Default: 0<br>Is the server pausable.
sv_pause_on_console_open | a | Default: false<br>1 = Pause the game when pressing ~ to open the console. CTRL+~ opens the console without pause.
sv_per_player_spray_limit_count | sv, release | Default: 200<br>How many total sprays each player can have in the map at the same time
sv_per_player_spray_limit_count_restricted | sv, release | Default: 20<br>How many total sprays each player can have in the map at the same time (but in restricted modes)
sv_phys_debug_callback_entities | sv, cheat | Default: false<br>Print all entities that get touch callbacks. Each entity is printed only once.
sv_phys_enabled | sv, cheat | Default: true<br>Enable all physics simulation
sv_phys_sleep_enable | sv, cheat | Default: true<br>Enable sleeping for dynamic physics bodies.
sv_phys_sound_disable_impact_sounds_under_hard_threshold | sv, cheat | Default: false<br>if true, impact sounds wont play if no soft impact sound is present and the impact is below the hard velocity threshold.
sv_phys_stop_at_collision | sv, cheat | Default: <br>
sv_play_stats_CitadelHitMismatch_enabled | sv, release | Default: false<br>Enable / Disable Play Stat CitadelHitMismatch.
sv_play_stats_CitadelLaneMatchup_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelLaneMatchup.
sv_play_stats_CitadelLaneSwap_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelLaneSwap.
sv_play_stats_CitadelLaneTrooperOrbs_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelLaneTrooperOrbs.
sv_play_stats_CitadelMatch_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelMatch.
sv_play_stats_CitadelObjective_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelObjective.
sv_play_stats_CitadelPerfStats_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelPerfStats.
sv_play_stats_CitadelPlayer_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelPlayer.
sv_play_stats_CitadelServerLobby_enabled | sv, release | Default: true<br>Enable / Disable Play Stat CitadelServerLobby.
sv_play_stats_CitadelTrooperUnstick_enabled | sv, release | Default: false<br>Enable / Disable Play Stat CitadelTrooperUnstick.
sv_play_stats_S2MatchPerf_enabled | sv, release | Default: true<br>Enable / Disable Play Stat S2MatchPerf.
sv_pvs_max_distance | rep, release | Default: 0<br>if set, adds a maximum range to PVS/PAS checks
sv_pvs_shadows_include_env | sv, rep, release | Default: false<br>
sv_ragdoll_lru_debug | sv, rep, cheat | Default: false<br>
sv_recipients_check | release | Default: true<br>When packing entities, check that recipient bits match for fast path packing.
sv_regeneration_force_on | sv, cheat | Default: false<br>Cheat to test regenerative health systems
sv_region | release | Default: -1<br>The region of the world to report this server in.
sv_replay_group_id | release | Default: 0<br>The replay group that this server will be uploading files to
sv_search_key | release | Default: <br>
sv_setsteamaccount | release | token<br>Set game server account token to use for logging in to a persistent game server account
sv_showlagcompensation | sv, cl, rep, cheat | Default: 0<br>If &gt; 0, show lag compensated hitboxes whenever a player is lag compensated. Value is for how long.
sv_shutdown | release | Sets the server to shutdown when all games have completed
sv_skel_constraints_enable | rep, cheat | Default: false<br>
sv_skyname | sv, cl, a, rep | Default: sky_urb01<br>Current name of the skybox texture
sv_snapshot_unlimited | rep, release | Default: false<br>For debugging, don't throw away old snapshots so that if you break in debugger (on remote client or server) it won't require an uncompressed update to resume.  You may run out of memory of course...
sv_soundscape_printdebuginfo | sv, cheat | print soundscapes
sv_specaccelerate | sv, cl, a, nf, rep | Default: 5<br>
sv_specnoclip | sv, cl, a, nf, rep | Default: true<br>
sv_specspeed | sv, cl, a, nf, rep | Default: 1200<br>
sv_spewmeta | cheat | Spew serializer meta
sv_steamauth_enforce | release | Default: 2<br>By default, player must maintain a reliable connection to Steam servers. When player Steam session drops, enforce it: 2 = instantly kick, 1 = kick at next spawn, 0 = do not kick.
sv_steamauth_ignore_localhost | release | Default: true<br>Ignore VAC and auth errors for client connected via localhost address or in-engine loopback
sv_steamgroup | nf, release | Default: <br>The ID of the steam group that this server belongs to. You can find your group's ID on the admin profile page in the steam community.
sv_steamgroup_exclusive | release | Default: false<br>If set, only members of Steam group will be able to join the server when it's empty, public people will be able to join the server only if it has players.
sv_stopspeed | sv, cl, nf, rep, release | Default: 100<br>Minimum stopping speed when on ground.
sv_stressbots | release | Default: false<br>If set to 1, the server calculates data and fills packets to bots. Used for perf testing.
sv_tags | nf, release | Default: <br>Server tags. Used to provide extra information to clients when they're browsing for servers. Separate tags with a comma.
sv_unlockedchapters | a | Default: 1<br>Highest unlocked game chapter.
sv_unpause_on_console_close | a | Default: false<br>1 = Unpause the game when pressing ~ to close the console. 0 = Leave the game paused.
sv_usercmd_custom_random_seed | sv, release | Default: false<br>When enabled server will populate an additional random seed independent of the client
sv_usercmd_execute_warning_ms | sv, a | Default: 5<br>Emit a warning if we spend more than N ms executing user commands for a single player
sv_vac_webapi_auth_key | sv, release | Default: <br>Key for when posting to vac related webapis.
sv_visiblemaxplayers | release | Default: -1<br>Overrides the max players reported to prospective clients
sv_voicecodec | release | Default: vaudio_speex<br>Specifies which voice codec DLL to use in a game. Set to the name of the DLL without the extension.
sv_voiceenable | a, nf, release | Default: true<br>
sv_watchtransmit | sv, release | Default: -2<br>Watch NetworkStateChanged info for this entity index.
sv_wateraccelerate | sv, cl, nf, rep, release | Default: 10<br>
sv_waterfriction | sv, cl, nf, rep, release | Default: 1<br>
sys_info | release | Print system information to the console
sys_minidumpspewlines | release | Default: 2000<br>Lines of crash dump console spew to keep.
team_chat_auto_join | cl, a, release | Default: false<br>Auto-join Team Chat when joining a match. Will be overridden by any party settings.
telemetry_message | sv, cheat | Place a message in the telemetry timeline
telemetry_toggle_timespan | sv, cheat | Starts/stops a timespan with an ever increasing name.
test_dispatcheffect | sv, cheat | Test a clientside dispatch effect.<br>	Usage: test_dispatcheffect &lt;effect name&gt; &lt;distance away&gt; &lt;flags&gt; &lt;magnitude&gt; &lt;scale&gt;<br>	Defaults are: &lt;distance 1024&gt; &lt;flags 0&gt; &lt;magnitude 0&gt; &lt;scale 0&gt;<br>
test_entity_blocker | sv, cheat | Test command that drops an entity blocker out in front of the player.
test_list_entities | sv, cheat | test-list entities
test_play_stats_send | sv, cheat | 
test_shipping_assert | release | Generate an assert to test shipping assertion code
think_limit | sv, cl, rep, release | Default: 10<br>Maximum think time in milliseconds, warning is printed if this is exceeded.
thirdperson | cl, cheat, per_tick | Switch to thirdperson camera.
thirdperson_mayamode | cl, cheat | Switch to thirdperson Maya-like camera controls.
timedemo | release | Play a demo and report performance info.
timedemoquit | release | Play a demo, report performance info, and then exit
toggle | norecord, release | Toggles specified convar value on and off.
toggleconsole | norecord, release | Show/hide the console.
trooper_kill_all | sv, cheat | Kills all living troopers
trooper_kill_non_bosses | sv, cheat | Kills all non-boss living troopers
tv_advertise_watchable | prot, nf, norecord, release | Default: false<br>GOTV advertises the match as watchable via game UI, clients watching via UI will not need to type password
tv_allow_autorecording_index | sv, release | Default: -1<br>When &gt;=0 restricts autorecording only to the specified TV index
tv_allow_static_shots | sv, release | Default: true<br>Auto director uses fixed level cameras for shots
tv_autorecord | release | Default: false<br>Automatically records all games as SourceTV demos.
tv_autoretry | release | Default: true<br>Relay proxies retry connection after network timeout
tv_broadcast | release | Default: false<br>Automatically broadcasts all games as GOTV demos through Steam.
tv_broadcast1 | release | Default: false<br>Automatically broadcasts all games as GOTV\[1\] demos through Steam.
tv_broadcast_keyframe_interval | release | Default: 3<br>The frequency, in seconds, of sending keyframes and delta fragments to the broadcast relay server
tv_broadcast_keyframe_interval1 | release | Default: 3<br>The frequency, in seconds, of sending keyframes and delta fragments to the broadcast1 relay server
tv_broadcast_max_requests | release | Default: 20<br>Max number of broadcast http requests in flight. If there is a network issue, the requests may start piling up, degrading server performance. If more than the specified number of requests are in flight, the new requests are dropped.
tv_broadcast_max_requests1 | release | Default: 20<br>Max number of broadcast1 http requests in flight. If there is a network issue, the requests may start piling up, degrading server performance. If more than the specified number of requests are in flight, the new requests are dropped.
tv_broadcast_spew_threshold | release | Default: 0.1<br>The threshold, in seconds, that we'll spew about the snapshot tick
tv_broadcast_startup_resend_interval | release | Default: 10<br>The interval, in seconds, of re-sending startup data to the broadcast relay server (useful in case relay crashes, restarts or startup data http request fails)
tv_broadcast_status | release | Print out broadcast status
tv_broadcast_url | release | Default: http://localhost:8080<br>URL of the broadcast relay
tv_broadcast_url1 | release | Default: http://localhost:8080<br>URL of the broadcast relay1
tv_chatgroupsize | release | Default: 0<br>Set the default chat group size
tv_chattimelimit | release | Default: 0.2<br>Limits spectators to chat only every n seconds
tv_citadel_auto_record | sv, release | Default: true<br>If enabled, a demo will automatically be recorded for every game
tv_clients | release | Shows list of connected SourceTV clients.
tv_debug | release | Default: 0<br>SourceTV debug info.
tv_delay | sv, release | Default: 120<br>SourceTV broadcast delay in seconds
tv_delay1 | sv, release | Default: 15<br>SourceTV\[instance 1\] broadcast delay in seconds
tv_deltacache | release | Default: 2<br>Enable delta entity bit stream cache
tv_dispatchmode | release | Default: 1<br>Dispatch clients to relay proxies: 0=never, 1=if appropriate, 2=always
tv_enable | nf, release | Default: false<br>Activates SourceTV on server.
tv_enable1 | nf, release | Default: false<br>Activates SourceTV\[1\] on server.
tv_enable_delta_frames | release | Default: true<br>Indicates whether or not the tv should use delta frames for storage of intermediate frames. This takes more CPU but significantly less memory.
tv_enable_dynamic | nf, release | Default: false<br>When enabled, changes in tv_enable convars cause immediate startup or shutdown of hltv server
tv_include_usercommands | sv, release | Default: true<br>HLTV streams will include player usercommands each tick
tv_listen_voice_indices | cl, user | Default: 0<br>Bitfield of playerslots to listen to voice messages from when connected to SourceTV, default is none
tv_listen_voice_indices_h | cl, user | Default: 0<br>High 32 bits of bitfield of playerslots to listen to voice messages from when connected to SourceTV, default is none
tv_maxclients | release | Default: 128<br>Maximum client number on SourceTV server.
tv_maxclients_relayreserved | release | Default: 0<br>This number of relay client connections are reserved for SourceTV relays.
tv_maxrate | release | Default: 0<br>Max SourceTV spectator bandwidth rate allowed, 0 == unlimited
tv_mem | release | hltv memory statistics. Use with "ent 10" (dump entity 10 memory usage) or "top 8" (dump top 8 memory users) or "class" CWorld (dump CWorld class)
tv_name | release | Default: SourceTV<br>SourceTV host name
tv_nochat | a, user | Default: false<br>Don't receive chat messages from other SourceTV spectators
tv_overridemaster | release | Default: false<br>Overrides the SourceTV master root address.
tv_password | prot, nf, norecord, release | Default: <br>SourceTV password for all clients of CSTV\[0\]
tv_password1 | prot, nf, norecord, release | Default: <br>SourceTV password for all clients of CSTV\[1\]. If empty, tv_password is used
tv_playcast_delay_prediction | release | Default: true<br>
tv_playcast_delay_resync | release | Default: 0<br>To alleviate intermittent network connectivity problems, this is the number of seconds to wait before actually re-syncing the stream after failure
tv_playcast_fragment_cache_history_length | release | Default: 120<br>How far back before our current playback head in seconds to hold onto fragments.
tv_playcast_retry_timeout | release | Default: 25<br>In case of intermittent network problems, how long should playcast retry fragment retrieval before resorting to resync
tv_port | release | Default: 27020<br>Host SourceTV\[0\] port
tv_port1 | release | Default: 27021<br>Host SourceTV\[1\] port
tv_record | release | Starts SourceTV demo recording.
tv_record_immediate | release | Default: 0<br>tv_record starting the moment tv_record was executed, not tv_delay earlier
tv_relay | release | Connect to SourceTV server and relay broadcast.
tv_relaypassword | prot, nf, norecord, release | Default: <br>SourceTV password for relay proxies
tv_relayvoice | release | Default: true<br>Relay voice data: 0=off, 1=on
tv_retry | release | Reconnects the SourceTV relay proxy.
tv_secure_bypass | release | Default: false<br>Bypass secure challenge on TV port
tv_show_allchat | sv, release | Default: true<br>
tv_snapshotrate | rep, release | Default: 20<br>Snapshots broadcast per second
tv_snapshotrate1 | release | Default: 32<br>Snapshots broadcast per second, GOTV\[1\]
tv_status | release | Show SourceTV server status.
tv_stop | release | Stops the SourceTV broadcast.
tv_stoprecord | release | Stops SourceTV demo recording.
tv_timeout | release | Default: 20<br>SourceTV connection timeout in seconds.
tv_title | release | Default: SourceTV<br>Set title for SourceTV spectator UI
tv_transmitall | rep, release | Default: false<br>Transmit all entities (not only director view)
tv_window_size | release | Default: 16<br>Specifies the number of seconds worth of frames that the tv replay system should keep in memory. Increasing this greatly increases the amount of memory consumed by the TV system
unbind | release | Unbind a key.
unbindall | release | Unbind all keys.
unpause | release | Clear the pause state of the server.
vconsole_rcon_server_details | norecord, release, server_cannot_query | Default: <br>when non-empty allows for easy vconsole connection to the dedicated server.
viewmodel_fov | cl, cheat | Default: 54<br>
violence_ablood | a | Default: true<br>Draw alien blood
violence_agibs | a | Default: true<br>Show alien gib entities
violence_hblood | a | Default: true<br>Draw human blood
violence_hgibs | a | Default: true<br>Show human gib entities
vis_force | sv, cheat | Default: false<br>
vismon_poll_frequency | sv, cheat | Default: 0.5<br>
vismon_trace_limit | sv, cheat | Default: 12<br>
vmix_input | cheat | Set an input mix value
vmix_output | cheat | Dump main graph control output values
voice_always_sample_mic | a | Default: false<br>When enabled, open the voip audio input stream when the application launches.
voice_device_override | a, release | Default: <br>Default device used for voice capture.
voice_input_stallout | user | Default: 0.5<br>Time before we consider a mic stalled out and need to reset it.
voice_loopback | user | Default: false<br>
voice_loopback_no_networking | user | Default: false<br>
voice_modenable | cl, a, release, clientcmd_can_execute | Default: true<br>Enable/disable voice in this mod.
voice_player_speaking_delay_threshold | sv, cheat | Default: 0.5<br>
voice_threshold | cl, a | Default: -120<br>decibel threshold for how loud the talker's input signal is before we think they are talking.
voice_vox | cl, a, per_user, release | Default: 0<br>Voice chat uses a vox-style always on
volume | a | Default: 1<br>Sound volume
volume_fog_debug_volumes | cheat | Default: false<br>
volume_fog_dither_scale | cheat | Default: 1<br>
volume_fog_enable_jitter | cheat | Default: true<br>
warp_onto_zipline | sv, cheat | warp onto the nearest point of the zipline lane passed in.  provides the zipline intro modifier as well
wrecking_ball_muddy | sv, cheat | Default: 0.8<br>The extent to which the Wrecker's boulder behaves 'muddy', meaning how much its jumps up are dampened
writekeybindings | release | Saves current key bindings to disk.
zoom_sensitivity_ratio | cl, a, per_user | Default: 1<br>Additional mouse sensitivity scale factor applied when FOV is zoomed in.
