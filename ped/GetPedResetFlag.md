---
ns: PED
aliases: ["0xaf9e59b1b1fbf2a0"]
---
## GET_PED_RESET_FLAG

```c
// 0xAF9E59B1B1FBF2A0
bool GET_PED_RESET_FLAG(Ped ped, int ResetFlag);
```

Gets the given ped reset flag bit

## ResetFlag Values:
| Value | Name |
| --- | --- |
| 462 |  Fallen Down |
| 463 |  Dont Render This Frame |
| 464 |  Is Drowning |
| 465 |  Ped Hit Wall Last Frame |
| 466 |  Using Mobile Phone |
| 467 |  Block Movement Anims |
| 468 |  Zero Desired Move Blend Ratios |
| 469 |  Dont Change Mbr In Simple Move Do Nothing |
| 470 |  Following Route |
| 471 |  Taking Route Spline Corner |
| 472 |  Wandering |
| 473 |  Process Physics Tasks |
| 474 |  Process Pre Render2 |
| 475 |  Set Last Matrix Done |
| 476 |  Firing Weapon |
| 477 |  Searching For Cover |
| 478 |  Keep Cover Point |
| 479 |  Is Climbing |
| 480 |  Is Jumping |
| 481 |  Is Landing |
| 482 |  Cull Extra Far Away |
| 483 |  Dont Activate Ragdoll From Any Ped Impact Reset |
| 484 |  Force Script Controlled Ragdoll |
| 485 |  Task Use Kinematic Physics |
| 486 |  Temporarily Block Weapon Switching |
| 487 |  Do Not Clamp Foot Ik |
| 488 |  Move Blend B Flee Task Running |
| 489 |  Is Aiming |
| 490 |  Move Blend B Task Complex Gun Running |
| 491 |  Move Blend B Melee Task Running |
| 492 |  Move Blend B Cop Search Task Running |
| 493 |  Patrolling In Vehicle |
| 494 |  Raise Velocity Change Limit |
| 495 |  Dim Target Reticule |
| 496 |  Is Walking Round Player |
| 497 |  Gesture Anims Allowed |
| 498 |  Viseme Anims Blocked |
| 499 |  Ambient Anims Blocked |
| 500 |  Knocked To The Floor By Player |
| 501 |  Randomise Points During Navigation |
| 502 |  Prevent180 Skid Turns |
| 503 |  Is On Assisted Movement Route |
| 504 |  Apply Velocity Directly |
| 505 |  Disable Player Lockon |
| 506 |  Reset Move Group After Ragdoll |
| 507 |  Disable Ped Constraints |
| 508 |  Disable Player Jumping |
| 509 |  Disable Player Vaulting |
| 510 |  Disable Asleep Impulse |
| 511 |  Force Post Camera Aiupdate |
| 512 |  Force Post Camera Anim Update |
| 513 | E Post Camera Anim Update Use Zero Timestep |
| 514 |  Collide With Glass Ragdoll |
| 515 |  Collide With Glass Weapon |
| 516 |  Sync Desired Heading To Current Heading |
| 517 |  Allow Update If No Collision Loaded |
| 518 |  Internal Walking Rnd Player |
| 519 |  Placing Charge |
| 520 |  Script Disable Secondary Animation Tasks |
| 521 |  Searching For Climb |
| 522 |  Searching For Doors |
| 523 |  Wandering Stopped For Other Ped |
| 524 |  Supress Gunfire Events |
| 525 |  Infinite Stamina |
| 526 |  Block Weapon Reactions Unless Dead |
| 527 |  Force Player Firing |
| 528 |  In Cover Facing Left |
| 529 |  Force Peek From Cover |
| 530 |  Not Allowed To Change Crouch State |
| 531 |  Force Ped To Strafe |
| 532 |  Force Melee Strafing Anims |
| 533 |  Hit Ped With Weapon |
| 534 |  Force Ped To Use Scrip Cam Heading |
| 535 |  Process Probes When Extracting Z |
| 536 |  Keep Desired Cover Point |
| 537 |  Has Processed Cornering |
| 538 |  Standing On Forklift Forks |
| 539 |  Aim Weapon Reaction Running |
| 540 |  In Contact With Foliage |
| 541 |  Force Explosion Collisions |
| 542 |  Ignore Targets Cover For Los |
| 543 |  Block Animated Weapon Reactions |
| 544 |  Disable Ped Capsule |
| 545 |  Disable Crouch While In Cover |
| 546 |  Increased Avoidance Radius |
| 547 |  Unused  Replace  Me |
| 548 |  Force Running Speed For Frag Smashing |
| 549 |  Enable Mover Animation While Attached |
| 550 |  No Time Delay Before Shot |
| 551 |  Searching For Auto Vault Climb |
| 552 |  Extra Long Weapon Range |
| 553 |  Force Player To Enter Vehicle Through Direct Door Only |
| 554 |  Task Cull Extra Far Away |
| 555 |  Is Vaulting |
| 556 |  Is Parachuting |
| 557 |  Suppress Slowing For Corners |
| 558 |  Disable Process Probes |
| 559 |  Disable Player Auto Vaulting |
| 560 |  Disable Gait Reduction |
| 561 |  Exit Vehicle Task Finished This Frame |
| 562 |  Requires Leg Ik |
| 563 |  Jay Walking |
| 564 |  Use Bullet Penetration |
| 565 |  Force Aim At Head |
| 566 |  Is In Stationary Scenario |
| 567 |  Temporarily Block Weapon Equipping |
| 568 |  Cover Outro Running |
| 569 |  Disable See Through Checks When Targeting |
| 570 |  Putting On Helmet |
| 571 |  Allow Pulling Ped Onto Route |
| 572 |  Apply Animated Velocity Whilst Attached |
| 573 |  Aicover Entry Running |
| 574 |  Response After Scenario Panic |
| 575 |  Is Near Door |
| 576 |  Disable Torso Solver |
| 577 |  Panic In Vehicle |
| 578 |  Disable Dynamic Capsule Radius |
| 579 |  Is Rappelling |
| 580 |  Skip React In React And Flee |
| 581 |  Cannot Be Targeted |
| 582 |  Is Falling |
| 583 |  Force Injury After Stunned |
| 584 |  Hurt This Frame |
| 585 |  Block Weapon Fire |
| 586 |  Expand Ped Capsule From Skeleton |
| 587 |  Disable Weapon Laser Sight |
| 588 |  Ped Exited Vehicle This Frame |
| 589 |  Searching For Drop Down |
| 590 |  Use Tighter Turn Settings |
| 591 |  Disable Arm Solver |
| 592 |  Disable Head Solver |
| 593 |  Disable Leg Solver |
| 594 |  Disable Torso React Solver |
| 595 |  Force Pre Camera Aiupdate |
| 596 |  Tasks Need Process Move Signal Calls |
| 597 |  Shoot From Ground |
| 598 |  No Collision Movement Mode |
| 599 |  Is Near Laddder |
| 600 |  Skip Aiming Idle Intro |
| 601 |  Ignored By Auto Open Doors |
| 602 |  Block Ik Weapon Reactions |
| 603 |  First Physics Update |
| 604 |  Spawned This Frame By Ambient Population |
| 605 |  Disable Root Slope Fixup Solver |
| 606 |  Suspend Initiated Melee Actions |
| 607 |  Suppress In Air Event |
| 608 |  Allow Tasks Incompatible With Motion |
| 609 |  Is Entering Or Exiting Vehicle |
| 610 |  Player On Horse |
| 611 |  Has Gun Task With Aiming State |
| 612 |  Suppress Lethal Melee Actions |
| 613 |  Instant Blend To Aim From Script |
| 614 |  Is Still On Bicycle |
| 615 |  Is Sitting And Cycling |
| 616 |  Is Standing And Cycling |
| 617 |  Is Doing Cover Aim Outro |
| 618 |  Apply Cover Weapon Blocking Offsets |
| 619 |  Is In Low Cover |
| 620 |  Ambient Idle And Base Anims Blocked |
| 621 |  Use Alternative When Block |
| 622 |  Force Low Lod Water Check |
| 623 |  Make Head Invisible |
| 624 |  No Auto Run When Firing |
| 625 |  Permit Event During Scenario Exit |
| 626 |  Disable Steering Around Vehicles |
| 627 |  Disable Steering Around Peds |
| 628 |  Disable Steering Around Objects |
| 629 |  Disable Steering Around Nav Mesh Edges |
| 630 |  Wants To Enter Vehicle From Cover |
| 631 |  Wants To Enter Cover |
| 632 |  Wants To Enter Vehicle From Aiming |
| 633 |  Capsule Being Pushed By Vehicle |
| 634 |  Disable Take Off Parachute Pack |
| 635 |  Is Calling Police |
| 636 |  Force Combat Taunt |
| 637 |  Ignore Combat Taunts |
| 638 |  Skip Ai Update Process Control |
| 639 |  Override Physics |
| 640 |  Was Physics Overridden |
| 641 |  Block Weapon Holding Anims |
| 642 |  Disable Move Task Heading Adjustments |
| 643 |  Disable Body Look Solver |
| 644 |  Prevent All Melee Takedowns |
| 645 |  Prevent Failed Melee Takedowns |
| 646 |  Is Pedalling |
| 647 |  Use Tighter Avoidance Settings |
| 648 |  Is Higher Priority Clip Controlling Ped |
| 649 |  Vehicle Crushing Ragdoll |
| 650 |  On Activation Update |
| 651 |  Force Motion State Leave Desired Mbr |
| 652 |  Disable Drop Downs |
| 653 |  In Contact With Bigfoliage |
| 654 |  Disable Take Off Scuba Gear |
| 655 |  Disable Cellphone Animations |
| 656 |  Is Exiting Vehicle |
| 657 |  Disable Action Mode |
| 658 |  Equipped Weapon Changed |
| 659 |  Touching Overhang |
| 660 |  Too Steep For Player |
| 661 |  Block Secondary Anim |
| 662 |  Is In Combat |
| 663 |  Use Head Orientation For Perception |
| 664 |  Is Doing Driveby |
| 665 |  Is Entering Cover |
| 666 |  Force Movement Scanner Check |
| 667 |  Disable Jump Ragdoll On Collision |
| 668 |  Is Being Melee Homed By Player |
| 669 |  Should Launch Bicycle This Frame |
| 670 |  Can Do Bicycle Wheelie |
| 671 |  Force Process Physics Update Each Sim Step |
| 672 |  Disable Ped Capsule Map Collision |
| 673 |  Disable Seat Shuffle Due To Injured Driver |
| 674 |  Disable Parachuting |
| 675 |  Process Post Movement |
| 676 |  Process Post Camera |
| 677 |  Process Post Pre Render |
| 678 |  Prevent Bicycle From Leaning Over |
| 679 |  Keep Parachute Pack On After Teleport |
| 680 |  Dont Raise Fists When Locked On |
| 681 |  Prefer Melee Body Ik Hit Reaction |
| 682 |  Process Physics Tasks Motion |
| 683 |  Process Physics Tasks Movement |
| 684 |  Disable Friendly Gun React Audio |
| 685 |  Disable Agitation Triggers |
| 686 |  Force Forward Transition In React And Flee |
| 687 |  Is Entering Vehicle |
| 688 |  Do Not Skip Nav Mesh Tracker Update |
| 689 |  Ragdoll On Vehicle |
| 690 |  Block Ragdoll Activation In Vehicle |
| 691 |  Disable Nmfor River Rapids |
| 692 |  Is In Writhe |
| 693 |  Prevent Going Into Still In Vehicle State |
| 694 |  Use Fast Enter Exit Vehicle Rates |
| 695 |  Disable Ground Attachment |
| 696 |  Disable Agitation |
| 697 |  Disable Talk |
| 698 |  Interrupted To Quick Start Engine |
| 699 |  Ped Entered From Left Entry |
| 700 |  Is Diving |
| 701 |  Disable Vehicle Impacts |
| 702 |  Deep Vehicle Impacts |
| 703 |  Disable Ped Capsule Control |
| 704 |  Use Probe Slope Stairs Detection |
| 705 |  Disable Vehicle Damage Reactions |
| 706 |  Disable Potential Blast Reactions |
| 707 |  Only Allow Left Arm Door Ik |
| 708 |  Only Allow Right Arm Door Ik |
| 709 |  Force Process Ped Standing Update Each Sim Step |
| 710 |  Disable Flash Light |
| 711 |  Doing Combat Roll |
| 712 |  Disable Body Recoil Solver |
| 713 |  Can Abort Exit For In Air Event |
| 714 |  Disable Sprint Damage |
| 715 |  Force Enable Flash Light For Ai |
| 716 |  Is Doing Cover Aim Intro |
| 717 |  Is Aiming From Cover |
| 718 |  Waiting For Completed Path Request |
| 719 |  Disable Combat Audio |
| 720 |  Disable Cover Audio |
| 721 |  Prevent Bike From Leaning |
| 722 |  In Cover Task Active |
| 723 |  Enable Steep Slope Prevention |
| 724 |  Inside Enclosed Search Region |
| 725 |  Jumping Out Of Vehicle |
| 726 |  Is Tucked On Bicycle This Frame |
| 727 |  Process Post Movement Time Sliced |
| 728 |  Enable Press And Release Dives |
| 729 |  Only Exit Vehicle On Button Release |
| 730 |  Is Going To Stand On Exited Vehicle |
| 731 |  Block Ragdoll From Vehicle Fall Off |
| 732 |  Disable Torso Vehicle Solver |
| 733 |  Is Exiting Upside Down Vehicle |
| 734 |  Is Exiting Onside Vehicle |
| 735 |  Is Exact Stopping |
| 736 |  Is Exact Stop Settling |
| 737 |  Is Train Crushing Ragdoll |
| 738 |  Override Hair Scale |
| 739 |  Consider As Player Cover Threat Without Los |
| 740 |  Block Custom Aientry Anims |
| 741 |  Ignore Vehicle Entry Collision Tests |
| 742 |  Stream Action Mode Anims If Disabled |
| 743 |  Force Update Ragdoll Matrix |
| 744 |  Prevent Going Into Shunt In Vehicle State |
| 745 |  Disable Independent Mover Frame |
| 746 |  Doing Driveby Outro |
| 747 |  Being Electrocuted |
| 748 |  Disable Unarmed Drivebys |
| 749 |  Talking To Player |
| 750 |  Dont Activate Ragdoll From Player Ped Impact Reset |
| 751 |  Dont Activate Ragdoll From Ai Ragdoll Impact Reset |
| 752 |  Dont Activate Ragdoll From Player Ragdoll Impact Reset |
| 753 |  Disable Viseme Body Additive |
| 754 |  Capsule Being Pushed By Player Capsule |
| 755 |  Force Action Mode |
| 756 |  Force Unarmed Action Mode |
| 757 |  Using Mover Extraction |
| 758 |  Being Jacked |
| 759 |  Enable Voice Driven Mouth Movement |
| 760 |  Is Reloading |
| 761 |  Use Tighter Enter Vehicle Settings |
| 762 |  In Race Mode |
| 763 |  Disable Ambient Melee Moves |
| 764 |  Force Buoyancy Processing If Asleep |
| 765 |  Allow Special Ability In Vehicle |
| 766 |  Disable In Vehicle Actions |
| 767 |  Force Instant Steering Wheel Ik Blend In |
| 768 |  Ignore Threat Engage Player Cover Bonus |
| 769 |  Block180 Turns |
| 770 |  Dont Close Vehicle Door |
| 771 |  Skip Explosion Occlusion |
| 772 |  Process Physics Tasks Time Sliced |
| 773 |  Melee Strike Against Non Ped |
| 774 |  Ignore Navigation For Door Arm Ik |
| 775 |  Disable Aiming While Parachuting |
| 776 |  Disable Ped Collision With Ped Event |
| 777 |  Ignore Velocity When Closing Vehicle Door |
| 778 |  Skip On Foot Idle Intro |
| 779 |  Dont Walk Round Objects |
| 780 |  Disable Ped Entered My Vehicle Events |
| 781 |  Cancel Left Hand Grip Ik |
| 782 |  Reset Movement Static Counter |
| 783 |  Disable In Vehicle Ped Variation Blocking |
| 784 |  Reduce Effect Of Vehicle Ram Control Loss |
| 785 |  Disable Player Melee Friendly Attacks |
| 786 |  Motion Ped Do Post Movement Independent Mover |
| 787 |  Is Melee Target Unreachable |
| 788 |  Disable Auto Force Out When Blowing Up Car |
| 789 |  Throwing Projectile |
| 790 |  Override Hair Scale Larger |
| 791 |  Disable Dust Off Anims |
| 792 |  Disable Melee Hit Reactions |
| 793 |  Viseme Anims Audio Blocked |
| 794 |  Allow Head Prop In Vehicle |
| 795 |  Is In Vehicle Chase |
| 796 |  Dont Quit Motion Aiming |
| 797 |  Set Last Bound Matrices Done |
| 798 |  Preserve Animated Angular Velocity |
| 799 |  Open Door Arm Ik |
| 800 |  Use Tighter Turn Settings For Script |
| 801 |  Force Pre Camera Process Externally Driven Dofs |
| 802 |  Ladder Blocking Movement |
| 803 |  Disable Voice Driven Mouth Movement |
| 804 |  Steer Into Skids |
| 805 |  Allow Open Door Ik Before Full Movement |
| 806 |  Allow Homing Missile Lock On In Vehicle |
| 807 |  Allow Clone Force Post Camera Aiupdate |
| 808 |  Disable High Heels |
| 809 |  Break Target Lock |
| 810 |  Dont Use Sprint Energy |
| 811 |  Dont Change Horse Mbr |
| 812 |  Disable Material Collision Damage |
| 813 |  Disable Mpfriendly Lockon |
| 814 |  Disable Mpfriendly Lethal Melee Actions |
| 815 |  If Leader Stops Seek Cover |
| 816 |  Process Post Pre Render After Attachments |
| 817 |  Do Damage Cough Facial |
| 818 |  Is Using Jetpack |
| 819 |  Use Interior Capsule Settings |
| 820 |  Is Closing Vehicle Door |
| 821 |  Disable Idle Extra Heading Change |
| 822 |  Only Select Vehicle Weapons |
| 823 |  Is Warping Into Vehicle Mp |
| 824 |  Remove Helmet |
| 825 |  Is Removing Helmet |
| 826 |  Gesture Anims Blocked From Script |
| 827 |  Never Ragdoll |
| 828 |  Disable Wall Hit Animation |
| 829 |  Play Agitated Anims In Vehicle |
| 830 |  Is Seat Shuffling |
| 831 |  Is Throwing Projectile While Aiming |
| 832 |  Disable Projectile Throws While Aiming Gun |
| 833 |  Allow Control Radio In Any Seat In Mp |
| 834 |  Disable Spycar Transformation |
| 835 |  Block Quad Locomotion Idle Turns |
| 836 |  Block Headbobbing To Radio |
| 837 |  Play Fpsidle Fidgets |
| 838 |  Force Extra Long Blend In For Ped Skip Idle Cover Transition |
| 839 |  Blending Out Fpsidle Fidgets |
| 840 |  Disable Motion Base Velocity Override |
| 841 |  Fpsswim Use Swim Motion Task |
| 842 |  Fpsswim Use Aiming Motion Task |
| 843 |  Firing Weapon When Ready |
| 844 |  Is Blind Firing |
| 845 |  Is Peeking From Cover |
| 846 |  Task Skip Process Pre Compute Impacts |
| 847 |  Disable Assisted Aim Lockon |
| 848 |  Fpsallow Aim Ikfor Thrown Projectile |
| 849 |  Trigger Road Rage Anim |
| 850 |  Force Pre Camera Ai Anim Update If First Person |
| 851 |  No Collision Damage From Other Peds |
| 852 |  Block Camera Switching |
| 853 |  Never Die From Capsule Ragdoll Settings |
| 854 |  In Contact With Deep Surface |
| 855 |  Dont Suppress Use Nav Mesh To Navigate To Vehicle Door When Vehicle In Water |
| 856 |  Include Ped Reference Velocity When Firing Projectiles |
| 857 |  Is Doing Cover Outro To Peek |
| 858 |  Instant Blend To Aim No Settle |
| 859 |  Force Pre Camera Anim Update |
| 860 |  Disable Helmet Cull Fps |
| 861 |  Should Ignore Cover Auto Heading Correction |
| 862 |  Disable Reticule In Cover This Frame |
| 863 |  Force Scripted Camera Low Cover Angle When Entering Cover |
| 864 |  Disable Camera Constraint Fall Back This Frame |
| 865 |  Disable Fpsarm Ik |
| 866 |  Disable Right Arm Ikin Cover Outro Fps |
| 867 |  Do Fpssprint Break Out |
| 868 |  Do Fpsjump Break Out |
| 869 |  Is Exiting Cover |
| 870 |  Weapon Blocked In Fpsmode |
| 871 |  Po Vcamera Constrained |
| 872 |  Script Clearing Ped Tasks |
| 873 |  Was Fpsjumping With Projectile |
| 874 |  Disable Melee Weapon Selection |
| 875 |  Waypoint Playback Slow More For Corners |
| 876 |  Fpsplacing Projectile |
| 877 |  Use Bullet Penetration For Glass |
| 878 |  Fpsplanting Bomb On Floor |
| 879 |  Force Skip Fpsaim Intro |
| 880 |  Can Be Pinned By Friendly Bullets |
| 881 |  Disable Left Arm Ikin Cover Outro Fps |
| 882 |  Disable Spike Strip Road Blocks |
| 883 |  Skip Fpsun Holster Transition |
| 884 |  Put Down Helmet Fx |
| 885 |  Is Lower Priority Melee Target |
| 886 |  Force Scan For Events This Frame |
| 887 |  Start Projectile Task With Priming Disabled |
| 888 |  Check Fpsswitch In Camera Update |
| 889 |  Force Auto Equip Helmets In Aicraft |
| 890 |  Block Remote Player Recording |
| 891 |  Inflicted Damage This Frame |
| 892 |  Use First Person Vehicle Anims If Fpscam Not Dominant |
| 893 |  Force Into Stand Pose On Jetski |
| 894 |  In Air Defence Sphere |
| 895 |  Suppress Takedown Melee Actions |
| 896 |  Invert Look Around Controls |
| 897 |  Ignore Combat Manager |
| 898 |  Use Blended Cameras On Update Fps Camera Relative Matrix |
| 899 |  Force Melee Counter |
| 900 |  Was Hit By Vehicle Melee |
| 901 |  Suppress Navmesh For Enter Vehicle Task |
| 902 |  Disable Shallow Water Bike Jump Out This Frame |
| 903 |  Disable Player Combat Roll |
| 904 |  Ignore Detach Safe Position Check |
| 905 |  Disable Easy Ladder Conditions |
| 906 |  Player Ignores Scenario Spawn Restrictions |
| 907 |  Using Drone |
| 908 |  Force Wanted Level When Killed |
| 909 |  Use Scripted Weapon Fire Position |
| 910 |  Enable Collision On Network Clone When Fixed |
| 911 |  Use Extended Ragdoll Collision Calculator |
| 912 |  Prevent Lockon To Friendly Players |
| 913 |  Only Abort Scripted Anim On Movement By Input |
| 914 |  Prevent All Stealth Kills |
| 915 |  Block Fall Task From Explosion Damage |
| 916 |  Allow Ped Rear Entry |


These flags are reset every frame

