# Build The Quickie Cheapie Tener
### *Perhaps the easiest way to get a 1 watt CW rig for the 10 meter band.*

Who says that one-transistor transmitters necessarily have to be unreliable toys? The output power may not be so high—that's quite obvious—but, if you choose the right project, you can be sure of building a little, perfect QRP transmitter while spending less than five bucks and with minimum effort. 
The 1 watt, 10 meter CW rig that's described here uses only 11 cheap, readily-available parts and their values aren't critical at all. This means that it will work as soon as its power supply is connected, assuming that all connections are right and are kept reasonably short and direct. 
It's a winning card for young experimenters taking their first steps as hams, and for older people who have never tried to build an RF circuit or who enjoy QRP operating. 

### A Look at the Circuit
Figure 1 shows the schematic diagram of the Quickie Cheapie Tener. It's nothing more than a quite straightforward Pierce crystal-controlled oscillator with tuned output, equipped with a medium-power NPN silicon transistor, like a 2N3866 or similar device. 

Basically, this circuit is a common-emitter amplifier. Resistors RI and R2 set a proper polarization voltage for the base, while R3 plays the same role for the emitter; that is, RF is bypassed to ground by means of capacitor C3. The connection of the XTAL (crystal) between the Q1 collector and base creates a feedback path that causes the stage to break into oscillation at the crystal frequency that may be modified by a few kHz by acting on trimmer capacitor C1. Fixed capacitor C2 just prevents collector DC from uselessly affecting the XTAL. and has practically no effect on output frequency. 

The collector circuit is tuned at crystal frequency by means of a toroidal inductor (L1) and a trimmer capacitor (C4) connected in parallel. A two-turn link, L2, allows the output signal on L1 to be fed to a resonating aerial by a coax cable. Capacitor C5 bypasses supply voltage and at the same time creates an RF path to ground for the output-tuned circuit. 

The transmitter requires a 12 to 20 VDC regulated power supply: this should deliver a continuous current of at least 300 mA. 

### Building the Quickie
The Quickie Cheapie Tener may be assembled just as you like, as long as you keep in mind that connections must be kept as short as possible. So, you can build it on a small piece of perfboard, or pick up a scrap of unetched PC material and adopt the "dead bug" technique. If you prefer a smarter and longer-lasting solution, just etch the PC board shown in Figure 2 (or better yet, drilled and etched PC hoards are available for $3.75 plus $1.50 S & H per order from FAR Circuits, 18N640 Field Court, Dundee, IL 60118). After etching, cleaning and drilling (use a #74-size drill bit for all holes), take a look at the parts layout shown in Figure 2 and start with installing resistors. Then go on with fixed and trimmer capacitors, and finally solder Q1 and the XTAL—unless you prefer to use a socket for this last item. 

Now it's time to wind up the coils. You need a small Amidon toroid core, like FT-37-2 or FT-37-6. Slightly different toroids will do if the ferrite mix is suitable for frequencies up to 30 MHz or more. Inductor L1 consists of 10 turns of #24 enameled copper wire: L2 is a two-turn link wound between the ends of L1, still using #24 wire. Before soldering L1 and L2, scrape away the enamel from the ends of the windings (about 1/4" is enough) with a sharp blade, then pre-tin them using a hot soldering iron. 

### Tuneup
If an outdoor antenna resonating on 28 MHz is not available, temporarily connect 5 to 10 feet of insulated copper wire to the output of the Quickie. You may also use a "dummy load" made by a small filament lamp—say, 6V, 100 mA. Its brightness will roughly tell how much RF energy is coming from the transmitter output. Put a communications receiver near the transmitter board and tune it to the XTAL frequency. Connect the Quickie to the power supply and slowly turn C4 with a plastic screwdriver (don't use metal tools!) until you can receive its carrier. Adjust C4 for maximum reading from the S-meter of your receiver, then set the exact transmission frequency by means of C1. 

This completes the tuneup of the transmitter. To send CW, connect a key in series with the positive or the negative rail of the power supply. It's advisable to put a 100,000 pF ceramic capacitor in parallel to the key in order to reduce manipulations or "clicks" due to current transients. If you have an FCC license, you are now ready for your first Quickie-QSO ( . . . or Quickie-DX, who knows!). Otherwise, just leave the dummy load lamp in place and use your brand new rig to take some exercise in Morse code. 

### Source: 
Veronese, Fabio. “Build the Quickie Cheapie Tener.” *73 Magazine*, Oct. 1994, pp. 36–37. 
*Internet Archive*, https://ia902608.us.archive.org/2/items/73-magazine-1994-10/10_October_1994.pdf#page=38. 
Accessed 28 Sept. 2022.
