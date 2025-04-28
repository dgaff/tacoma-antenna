# Introduction
This is a quick explanation for how to install a HAM (or CB) radio antenna on a 2017 Toyota Tacoma. I originally had my HAM radio antenna installed on a lip mount on the driver side door (using the [CP-5M Comet Universal RS-730 Lip Mount](https://www.amazon.com/dp/B0DF981DRJ)). I decided to move it to the back of the vehicle to reduce the radiation exposure inside the cab. My radio transmits 40 watts on the 2 m band.

![](IMG_0786.jpeg)

# Supplies
* Toyota [antenna tailgate mount](https://www.amazon.com/dp/B0CQSXMWGP/ref=pe_386300_440135490_TE_simp_item_imag)
* Antenna for your application. I'm using a [Comet CA-2X4SR](https://www.dxengineering.com/parts/cma-ca-2x4sr) for my HAM radio, which works on the 2 m and 70 cm bands.
* Antenna mount and cable. I'm using the NMO mount and attached cable that came with the Coment lip mount listed above, since that's what I had already.
* A couple 6mm x 1.0 x 20mm bolts
* A homemade ground strap

# Steps
First off, the routing of this cable requires that you don't have a plug on one end of your coax. The UHF plug (PL-259) on the Comet lip mount unscrews, so I removed the connector in order to thread the cable through the truck. If you're starting with coax cable that has no connectors, that will also work, of course.

![](IMG_0775.jpeg)

The cable will be routed behind the rear brake light assembly, through the upper frame of the truck bed, into the rear cab vent, behind the rear seat storage compartments, and then under the rear cargo mat to my radio body, which is located under the driver side seat. Note that I put the antenna on the passenger side of the tailgate. My truck's bed step is on the driver side, and that's the side I use to climb into the bed. So I didn't want an antenna there.

## Step 1 - Remove the rear tail light assembly.
Unscrew the two 10 mm bolts circled in the picture. Go slow with this. My trunk has 100,000 miles on it, and the bottom bolt was so rusted that when I unscrewed it, I snapped the plastic in the tail light that was holding the retainer. Boo! (I epoxied it back together.) So, unscrew cautiously with a socket wrench and not an impact driver. When the bolts are out, pull the top of the tail light towards you, and then pull the bottom away from the truck. There are two pressed-in retainers that will release.

![](IMG_0776.jpeg)

## Step 2 - Install the antenna mounting bracket.

The mounts I purchased attach to the two bed bolts shown in the picture. I had to bend the mount slightly so that it would clear the tailgate when it opens and closes, but otherwise, this antenna mount is an excellent fit.

As you can see in the picture, the second fastener isn't a bolt anymore. That's because I broke the head off the bolt when I was getting it out. I had to drill it out, and all I had on hand was a 6 mm allen head screw. I suggest soaking those bolts in WD-40 before attempting to unscrew them. You will also need to drill out the hole in the antenna mounting bracket to fit the diameter of your antenna mount.

![](IMG_0761.jpeg)

![](IMG_0760.jpeg)

![](IMG_0778.jpeg)

## Step 3 - Route the cable through the upper frame of the truck bed.

This is the trickiest part. First, remove the Tonneau Cover if you have one. Next, you'll need to remove the plastic trim on the top of the bed. This trim just pulls straight up, since it's held in place with clip fasteners. This will expose the channel through which the cable will be routed.

![](IMG_0780.jpeg)

Next, you may have to drill out the small hole that goes into the bed channel. If you look up into the tail light cavity, you'll see a small hole. I drilled this out slightly larger so it would accommodate the plug on my coax, but if you're running coax with no connectors, you won't need to make the hole bigger. I also installed a rubber grommet in this hole, just to provide additional protection for the coax.

![](IMG_0777.jpeg)

![](IMG_0763.jpeg)

On the other end of the channel, pull out the little rubber plug shown in the picture below. This will give you access to where the cable will come out.

![](IMG_0762.jpeg)

To run the cable through the channel, I just used some needle-nose pliers to hold the cable in place while I snaked it through the channel. I wanted it to sit on the top of the channel rather than fall into the bed sidewalls. It took a few tries to make this happen. To secure the cable tightly, zip-tie the end near the antenna mount. I used a zip tie post.

![](IMG_0781.jpeg)

## Step 4 - Remove the storage compartments from behind the rear seats.

Tilt both rear seats down, remove the headrests, and tilt both rear seat backs all the way flat. Unscrew the 6 bolts in the rear storage compartments. I've circled the 3 on the passenger side. The driver's side also has three similar bolts. Then pull the trim away, starting at the top. The trim is held in place by retainer clips that will release when you pull on them. This will expose the rear wall of the cable. The vents are underneath that insulation flap.

![](IMG_0782.jpeg)

![](IMG_0783.jpeg)

## Step 5 - Route the cable into the rear cab vent and along the back wall of the cab.

As you can see from the pictures, the cable goes into the vent and then along the back wall of the cab. It then comes out under the rear seat, goes under the rubber floor mat, and under the driver's side seat. I drilled a couple of small holes in the vent's interior housing to attach a zip tie and secure the cable.

![](IMG_0765.jpeg)

![](IMG_0764.jpeg)

![](IMG_0766.jpeg)

![](IMG_0784.jpeg)

## Step 6 - Ground strap.

The mounts I purchased are powder-coated and therefore have no exposed metal to provide a good frame ground. To fix this, I made a ground strap wire that screws in the base of the NMO mount and then attaches to one of the bolts on the antenna mount bracket. I also replaced the factory bolt with an uncoated 6mm bolt. The uncoated bolt ensures conductivity between the ground strap and the frame.

![](IMG_0785.jpeg)

## Step 7 - Test!

Please test everything before reinstalling the trim!

1. With your UHF connector disconnected from the radio, check continuity of the cable from the UHF connector to the antenna mount. Check both the center conductor and the shield!
2. With your UHF connector disconnected from the radio, check continuity of the shield on the antenna mount to your truck frame. It can be challenging to find a good point on the frame to pull a ground measurement, because the frame is usually coated and non-conductive. Look for an exposed bolt.
3. With the antenna mounted, measure SWR with a VNA. This allows you to find any major issues before sending a bunch of power down the cable.
4. With the antenna mounted, measure SWR with an SWR meter. You can do a quick tuning now, but mostly you're just looking for major problems.

I've had a coax failure before, so those continuity tests are really important. And if you don't have a solid frame ground, you need to fix that before doing an SWR test. 

<img src="meter.png" width=200px/> <img src="vna.png" width=300px/> <img src="swr.png" width=350px/>

## Step 8 - Reinstall the trim.

Reinstall the rear seat storage. Reinstall the bed trim and the bed cover. Reinstall the tail light. Pro tip: put some grease on the threads of the tail light bolts. If you ever have to remove the tail light again, a greased bolt comes out much easier.

It's a good idea to measure SWR again and do a fine-tuning. You're supposed to do SWR tuning in "real-world conditions." But let's face it, the performance is going to vary a bit if your truck bed is full of a bunch of metal objects vs. being empty. Try to get it as close to 1.5 as possible across your operating bands.

