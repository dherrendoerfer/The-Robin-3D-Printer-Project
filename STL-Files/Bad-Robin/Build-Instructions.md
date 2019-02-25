![Image](../../3D-Robins-Images/BR-v1-Image.png?raw=true)

### Build instructions:

## Part 1: Build the frame
# Prepare the Frame parts

Drill the holes to join the ITEM profiles.

The frame consists of three profiles, two of them need to be joined to the
third by drilling a hole for each joining part in it.

For the 250mm printer, the holes must be drilled in one axis at 130mm and the second
hole must be drilled at 200mm on the other axis. The bore diameter should be 6mm.

Take care, and make sure the holes are in the middle of the rod and at a perfect 90
degree angle. Use a drill press if available.

The Frame parts should be cleaned of any metal shavings or sharp edges.

# Assemble the frame

Using two 6mm threaded rods mount the two ITEM profiles to the profile with the 
two holes. Make sure that all parts are perfectly in line, and at 90 degree angles
to the center profile.

Tighten down the threaded rods well with M6 nuts. You can use glue on the profiles,
but you do not need to. One nut should be recessed inside the profile, the other open
at the profile end.

Finally add the feet using the 3D-printed parts and 20mm M5 screws and M5 T-nuts.

## Part 2: Add the Z-axis idler
# Choose your idler

There are two options available here, but one requires machining the threaded rod one
a lathe, creating a step with 5mm diameter one one side. 

The other idler just needs a small metal ball from a ball bearing to be inserted into its
center opening, and the threaded rod will rotate on that.

# Mounting the idler

Use the selected 3D-printed part, fit it onto the profile with a M5 T-nut and a 12mm M5
screw.


## Part 3: Mount the Arduino cradle

Use four M5 T-nuts and 12mm M5 screws to attach the cradle to the bottom of the frame
parallel to the short end of the X and Y-profile.

## Part 4: Assembling the Y-axis

Get the Y-axis motor mount 3D-printed part.

Cut two M5 hex head screws to 22mm. Put four 15mm M3 screws into the 3mm holes, make sure
screws fit well into the recess. Place the two 22mm M5 into the holes closest to the rail.
Screw a M5 nut onto each M5 screw, tighten that well. Add two 11x5x5mm bearings to each
screw, and fix them down with a M5 nut.

Screw the M3 screws carefully into the rail block, using a 1,3,2,4 pattern and fix with
reasonable force. Make sure that the rail is parallel to the bottom.

Add three 20mm M6, large washers, and M6 T-nuts to the part, to fix it to the profile.

Slide the Y-axis part onto the X-axis profile and tighten lightly.

Add the Y-axis belt holders to the end of the rail using 30mm M3 screws and M3 nuts

## Part 5: Assembling the X-axis

Get the X-axis motor mount 3D-printed part. Make sure the rail fits the grove in the 
part perfectly.

Place the rail over the 3D-printed part so that the 3mm hole in the grove closest to
the stepper position is not covered by the rail.

Place a 30mm M3 screw into the hole with the recess from back to the front where the
rail is. Add a M3 washer and a M3 nut onto the rail side and tighten well.

Repeat this for the next hole.

The third screw is screwed from the rail to the plastic. Use a 16mm M3 screw inserted into
the recess of the rail with a M3 nut on the plastic. Tighten well.

Get the linear rail for the Z-axis and screw the 3D-printed part with four 16mm M3 screws
into the rail block using 1,3,2,4 pattern and tighten well.

Optional: you may want to thread cable ties through the last holes and the back edge of
the rail to keep the block from sliding of the rail while building the printer.

Now slide the rail onto the Z-axis profile using two 16mm M3 screws and M3 T-nuts. Use the
second hole fron the top and bottom. Just tighten lightly, keep about 5cm distance to the 
Z-axis idler.

Then slide the Z-axis motor mount onto the top of the Z-axis profile using four 
12mm M5 screws and M5 T-nuts. Also tighten lightly. 

Fix the X-axis belt holder to the X-axis sliding block with a single M3 screw. 

Add the X-axis idler by screwing it to the rail using two 16mm M3 screws and M3 nuts.
Into the top and bottom hole of the idler place two 20mm M5 screws. On the rail side
add a 10x5mm washer, two 11x5x5mm bearings snd fix them with a M5 nut. Tighten well.
Insert a third 20mm M5 screw into the remaining hole and fix with a M5 nut.

## Part 6: Assembling the Z-axis

Assemble the Z-axis decoupler by fitting the TR8 hex nut guide over the TR8 nut making
sure that the guide sits on the nut tightly. Insert a 18mm M3 screw into the coupler
and into the guide and fix with a M3 nut.

Install the 11x5x5mm bearing into the Z-axis idler, or insert the ball bearing ball into 
the rod hole (depending on the type of idler you are using). Make sure that the lower edge
facing the profile is very clean, so the idler sits snug on the lower profile and the 
bearing to the threaded rod has no play.

Place the decoupler on the rod and insert the rod onto the idler. Slip the decoupler onto
two screws protruding fron the X-axis rail, the decouplers screw should be on the side of
the stepper.

## Part 7: Add the extruder mount

The extruder mount is is attached to the X-axis using two 10mm M3 screws at the lower two 
holes. Before mounting that, add a 10mm M3 screw and nut to the clamp of the Z-axis level
sensor. 

## Part 8: Mount the stepper motors

Mount the three NEMA17 steppers into their positions using 8mm or 10mm M3 screws and washers.
Don't forget to add the 5mm to 8mm coupler to the Z-axis rod and stepper. The Z-axis 
threaded rod and the stepper shaft should not be touching inside the coupler, but have
about 2mm of distance. 

## Part 9: Add the last X-axis belt idler

Below the X-axis stepper on the motor mount part, there is a 5mm hole, where the last belt 
idler needs to go. Put a 30mm M5 hex-head screw into this hole, add two M5 washers, then
two 11x5x5mm bearings and finally a M5 nut. tighten this well.

## Part 10: Fit the belts

Add a pulley to the X and Y-axis steppers. 

Start with the X-axis and thread the belt into the belt holder on the side facing the 
idler. The toothed side of the belt must be facing up, so the belt touches the bearings 
with the smooth side. Thread the belt around to the stepper, flipping it over between the
left and right idler on the bottom. Thread the belt into the side of the belt holder facing 
the stepper with the toothed side to the bottom. Tighten until there is no play in the 
printer carriage when the stepper is not turning. There does not need to be a lot of 
tension on the belt.

Add the belt to the Y-axis by mounting the belt to the holders and threading it around
the pulley via the bearings. Also tighten lightly to the point where there is no slack
in the belt.

## Part 11: Mount the level probe

Insert the level probe into the mount on the extruder mount assembly make sure it is able
move all the way down. Tighten slightly, make sure it sits snug in its place.

## Part 12: Prepare the extruder

Verify that the extruder has a PTFE liner inside the throat piece. Make sure that the 
temperature probe is fastened securely inside the block and that the heater does not
stick put of the front of the heater block by more than 2mm.

Choose a nozzle size. (Anything from 0.2 to 0.5mm should work well.)

Check that the nozzle is securely screwed into the heating block.

## Part 13: Mount the extruder

Place the extruder against the extruder mount, check that the cables exit to the back and
that the heating block is parallel to the mount so the heater cannot touch the fan holder.

Mount the extruder to the carriage by screwing two 30mm M3 screws trough the fan holder 
into the extruder mount, thereby clamping the extruder to the carriage and the mount.

Make sure that the fan holder is parallel to the mount. 

Check that the extruder is fastened securely.

## Part 14: Prepare the wiring 

Make sure that all cables for steppers, fan, switches, sensor and power supply have enough
length to reach the RAMPS board. 

For the switches you need to manufacture two sets of end switches, one should have about 
70cm cable length, the other about 20cm.

The cable for the fan should, in total, be about 70cm in length add a plug close to the 
fan to make replacing it easier.

The cables from the extruder and temp sensor should be long enough, if not: extend them to 
about 70cm.

The cable for the X-axis stepper should be about 70cm long, the Y-axis stepper needs just 
about 25cm of cable.

Also, make a power plug for the RAMPS board.

## Part 15: Add the Arduino and RAMPS boards 

Optional: Remove the power plug from the Arduino, in case it touches on the power connector
solder spots of the ramps too much.

Join the Arduino and RAMPS board.

Using thick double-sided tape stick the Arduino into the cradle,and make sure that it is
fastened well. The USB plug should go into the recess on the cradle and line up with that.

## Part 16: Mount the home switches

# X-axis
The X-axis home switch is placed on the small block on the extruder mount, and glued in
place there using hot glue. It should engage when the extruder is moved all the way into
the left position.

# Y-axis
The Y-axis home switched needs to be glued onto the Y-axis motor mount, so it engages when
the screw from the Y-axis belt holder comes closest to the front of the mount. Glue it in
place with hot glue and check that it engages when the Y-axis homes.

## Part 17: Add the extruder driver

Assemble the Tevo Titan extruder.

Enlarge the two mounting holes on the extruder driver mount to 5mm and fix the extruder
driver with two 12mm M5 screws and M5 T-nuts to the Z-axis profile. Keep about 13cm 
distance to the top of the profile.

## Part 18: Mount the PTFE feeder tube

Cut about 36cm PTFE tube (250mm model).

Push the PTFE feeder tube all the way into the extruder and the extruder driver.

## Part 19: Managing cables

Add two cable ties to the X-axis belt holder on the side of the X-axis idler.
With one of those cable ties fix down the belt to the holder, with the second cable
tie fix the extruder heater, and temperature sensor cable to the carriage, creating a 
cable loop large enough that the X-axis can travel all the way to the left and right. 
Check that the cables do not touch the rail or the idler.

Fix the fan to the fan mount with two 20mm M4 screws and M4 nuts.

Using a cable tie attach all cables from the X-axis carriage to the PTFE tube and route
all cables along the PTFE tube to the extruder driver.

Beyond the driver to the RAMPS board add the X and Z-axis stepper and the extruder driver 
stepper cable to the cable bundle and route all those down to the RAMPS board along the 
back of the Z-axis profile.

Use cable wrap to fix the cables together.

## Part 20: Adding connectors and firmware

Cut the cables to optimal length and add female connectors to the stepper and sensor 
cables.

Download and transfer the Repetier firmware to the Arduino. Use the firmware from this repo,
as the construction of the extruder requires a modified version of the Repetier firmware.

## Part 21: Connect the display unit

Mount the display unit into the display case, make sure that the reset switch and the 
SD-card are accessible and work. 

Add the display daughter board to the RAMPS board and connect it to the display with the
cables.

Add the stepper driver modules (X,Y,Z,E0) to the RAMPS board.


Optional: Fix the cables to the frame using hot-glue or double-sided tape.

## Part 22: Connect electronics to controller

Connect the home switches
- X home switch to Xmin pin.
- Y home switch to Ymin pin.
- Z level probe (output) to Zmax


Connect the positive and negative lead of the level probe (brown+,blue-) to the aux 12 
pins between the X stepper driver and the fuses. 


Connect the steppers (pins left to right)
- X-axis stepper to X (order: black,green,blue.red)
- Y-axis stepper to Y (order: black,green,blue.red)
- Z-axis stepper to Z (order: red,blue,green,black)
- Extruder driver stepper to E0 (order: black,green,blue.red)

Connect the temp sensor to T0


Connect the extruder heater to D10


Connect the extruder fan to D9, watch the polarity !


## Part 23: Test motors and switches

# 1st test
Connect the printer to power.

The display should come alive and the fan should spin up and run at high intensity for
about 15 seconds then the fan should ramp down to a low RPM but not stop.

# 2nd test
Using the display move each stepper using manual movement (fast) for 1mm.

The steppers should move in the right direction, they should not be emitting any noise
or vibrate. if yes, lower the current on the stepper.

# 3rd test
Heat the extruder to 170 degrees

The extruder should warm up. Abort the test once it passes 60 degrees Celsius.

# 4th test
Try to home X and Y-axis

The printer should move the axis to the home position

# 5th test
Navigate to the move Z-axis fast menu.

Place a metal object on the bottom of the Z-axis level sensor. The LED at the top
of the sensor should light up and the status for the end-stop should change on the 
display.

## Part 24: Finishing up

Mount the build platform to the Y-axis rail of the printer.

Glue the fan shroud to the fan outlet, making sure it is 1mm higher than the nozzle and
parallel to the table.

Measure that all axis are perpendicular to each other.

Measure that the table and the Z-axis rail are perfectly parallel.

Manually set the Z-axis to touch the table.

Push the level sensor down until it too touches the Table then turn the sensor one 
half turn counterclockwise. Perform a Z-axis homing. Adjust the height of the probe
by turning it until the Z-axis homes perfectly to touch the platform just barely.

Do a test print (Remember to add a G32 command on the last line to the init g-code for 
auto bed-leveling)
During the test print check the current to the extruder driver, keep an eye on the 
extruder temperature.
