Download Link: https://assignmentchef.com/product/solved-ee316-laboratory-09-and-10
<br>
Operating Characteristics of JFETsPurposeThe concept of the junction field effect transistor (JFET) is introduced. Understanding the configuration and states of JFETs will aid in the understanding of MOSFETs which will be introduced in later labs. Both NPN and PNP constructions are considered. Constants and variables relating to JFETs are discussed and utilized to convey a full understanding of the material. JFETs have high input impedance and low output noise. These features make JFETs ideal for small signal amplification. Unlike BJTs current can flow from drain to source or vice versa equally.Theoretical BackgroundConstruction – A JFET is constructed with four parts: a gate region, a body region, a drain region and a source region. The body is referred to as the channel if voltage in the gate is field affected. This puts the JFET into active mode allowing current to flow through the body. For an N-channel JFET the body is a P-type material, while the drain and source are both N-type. For a P-channel JFET the body is N-type, the drain and source are both Ptype. For ideal operation the material used to make the gate has no effect. Since the gate has no junctions, it can be modeled as a capacitor.Operation – Current flows through the body/channel region if the transistor is in linear operating mode. To get the JFET into linear operating mode you must appropriately bias the gate. The gate bias creates a channel through the body allowing current to flow. The voltage needed on the gate to put a JFET into linear operating mode is known as the threshold voltage. This gate voltage can be kept close to the threshold voltage relative to the source-drain voltage in order to make the JFET act as a current controlled device. Thus, the current can be maintained regardless of the drain to source voltage.

Figure 9.1 Symbolic representation

TermsThe terminals of JFETs use “D” to represent the drain, “S” to represent the source, “G” to represent the gate, and “B” to represent the body. The three operating states are known as Ohmic (linear), Saturation, and pinch-off. The threshold voltage (VTH) is used to represent the minimum value of the voltage required between the gate and source (VGS) in order to allow current to pass through the body. The pinch off voltage (VP) is the voltage beyond which the source current is constant (JFET is in saturation). VP is defined when the gate to source voltage is zero.Output characteristic V-I curves of a typical JFET:

Figure 9.2 Drain Characteristics

Figure 9.3 Transfer Characteristics

Circuit

Figure 9.4 JFET (2N3824) circuitTables:

Table 9.1Drain Characteristic (NPN 2N3824)VGS = 0 V VGS = -0.5 V VGS = -1 VVDS (V) Id (mA) Id (mA) Id (mA)00.51248121620

Table 9.2VDS = 6VVGS (V) Id (mA)0-0.5-1-1.5-2Procedure

1) Construct the circuit provided in Fig 9.4 and use the n-channel JFET 2N3824 in Multisim and 2N3819 in lab.

2) Obtain data to produce drain characteristic curves:a) Measure Id for the values of VDS indicated in Table 9.1 (note: you need to adjust V2 in order to set VDS to the values in the table. Thus, V2 does not equal VDS). While you do this adjust the value of V1 as needed to keep VGS = 0V.b) Repeat with VGS = -0.5V and -1.0Vc) Plot the data you recorded in Table 9.1. Your results should look like Fig 9.2. Based on your plot, estimate VP and VTH. Mark VP on your plot.

3) Obtain data to produce a transfer characteristic plota) Set V2 so that VDS = 6Vb) Adjust the value of V1 to obtain the values of VGS in Table 9.2. For each VGS measure Id. Your final value for Id should be 0 mA. If you do not get Id = 0 mA (or very close to it) then continue decreasing VGS below -2V until Id reaches 0 mA.c) Plot your results and estimate VP. Mark VP on your plot. Compare your estimation of VP in your drain and transfer characteristic analyses.

Reference:Electronic Devices and Circuit Theory, 7th Ed. by Robert Boylestad and Louis Nashelsky.Small Signal Amplification with JFETs (Lab 10)

Figure 10.1Procedure:

1 Build the circuit as shown in Fig. 10.1 in Multisim. Apply a small sinusoidal signal (Vpp=40mV) at the given frequency range (See table 10.1) using JFET 2N3824 (2N3819 in lab).

2 Based on your Table 10.1 results, plot voltage gain as a function of frequency and calculate the bandwidth. Identify the high and low cutoff frequencies. Note: plot frequency on a log scale.

a. In the lab the frequency generator has a maximum output frequency of 3 MHz and a minimum output voltage greater than 40 mV peak-to-peak. However, the 2N3819 that you will use in the lab has a much smaller bandwidth than the 2N3824 that you will simulate.

b. For the lab apply the minimum amplitude allowed by your frequency generator. Create your own table similar to Table 10.1 but with a maximum frequency of 3 MHz. Make sure you collect enough data points to plot the frequency response of the circuit in Fig. 10.1.

3 Comment on the phase relationship between the input and output waveforms

4 Compare and discuss your experimental and simulation results.Table 10.1Frequency (Hz) Vout (mV) Gain304560100200500100010000 (10 kHz)100000 (100 kHz)5000001000000 (1MHz)15000002000000300000040000005000000700000010000000 (10MHz)11000000120000001500000016000000