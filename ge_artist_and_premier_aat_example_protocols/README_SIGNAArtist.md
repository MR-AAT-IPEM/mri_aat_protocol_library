# GE SIGNA Artist 1.5T Wide bore

These example **MRI AAT** sequences are from a SIGNA Artist 1.5T Wide bore scanner, software version: MR30.0_R01_2242.a, Gradient Coil Type: XRMW, Gradient Amp Type: XG2 Gradients.

These example sequences are taken from common protocols in clinical use within an NHS Trust and are provided as both examples of sequence parameters using AAT and, where appropriate, for use on compatible systems.

Currently the following anatomical regions are included:
- Gad liver
- MRCP
- Knee
- Ankle
- Foot
- Hand
- Wrist 
- Shoulder
- Shoulder (fast)
- GYN screening pelvis
- Lumbar spine
- 3-part spine (fast)

Complete protocols are provided. For sequences with AAT applied look out for HyperSense (Compressed Sensing) and HyperBand Slice (simultaneous multi-slice acquisitions) under the Acceleration tab. For AIR Recon DL (deep learning reconstruction) see Recon DL Strength options: Off, Low, Medium, or High under the Details tab.

Sequence parameters are not provided in the PDFs which only give high level summary information. Copying the content of the folder ‘SIGNA Artist’ onto an external storage (blank USB or CD) and loading onto the scanner will upload the complete protocol(s). Information on how to use the Protocol Exchange tool on the scanner is provided in PDF form.

**Note:** *Image quality relies on the use of AATs, if the relevant option keys are not installed then images may be of lower quality (AIR Recon DL), or scan duration may be longer (HyperSense, HyperBand).

| Option key Guided Install name |	Short name	| Software version |	Protocol Information|
|---|---|---|---|
|AIRReconDL3D	|airrcndl3d|	30.0|	AIR Recon DL for 3D imaging|
|AIRReconDLPRP|	airrcndlpr|	30.0|	Enables DL Propeller when combined with airrcndl2d|
|AIRReconDL2D|	airrcndl2d|	MR29|	AIR Recon DL for 2D imaging|
|HyperSense_2|	hyprsense2|	MR29|	HyperSense 2.0 extends HS to 3D T1 sequences|
|Hypersense|	hypersense	| 27|	Provides scan time reduction technique while maintaining signal-to-noise ratio (SNR) through an innovative data compression algorithm for 3D|
|hyperband	|Hyperband	|27|	HyperBand reduces scan time by delivering multiple slices for single shot EPI/Diffusion in one go|

**Disclaimer:** *these protocols are in routine clinical use, but we provide no assurance regarding suitability for clinical use in your institution.  All sequences should be reviewed and approved locally prior to clinical use and we recommend an ongoing review process and assessment of image quality in a broad range of patients prior to local approval to use routinely.*
