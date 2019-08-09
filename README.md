# A Full-Desinged CHIP Applied For Vietnamese Single Word Recognition

This work is for “Develop speech recognition IC in 130nm TSMC technology integrated in the handset to support the blind people”project funded by Vietnamese Government. 

Well-designed chip namely iHearTech integrated Mel Frequency Cepstral Coefficients (MFCC) for feature extraction and Hidden Markov Model (HMM) algorithms for classification were successfully fabricated and evaluated on our own embedded application board. 

# Project Hierarchy:

 - 01_Publication_Doc:

    + 01_Technique Report For A Dynamic HMM Hardware Architecture For Recognition Application On TSMC 130nm Technology.pdf : Technique report for the IC

    + 02_VSR_IC Specification_V1.4.pdf: Specification of embedded system to verify the chip

    + 03_Doc_ref.tar : Specifications of realted IPs such as memory used for testing embedded system

- 02_Codes:

    + 01_HMM-Decoder.tar.gz: RTL Design (Verilog HDL) for HMM Decoder (Using Viterbi)

    + 02_Full_Chip.gz: RTL Desing (Verilog HDL) for full chip that is for fabrication

    + 03_Full_Chip_Verified_On_FPGA.gz: RTL Design (Verilog HDL) --> This version is for testing on FPGA

    + 04_Synthesize_wholechip_environment.tar.gz: Syntheis environment that is use to synthesize RTL Design (Verilog HDL) to Gate-Level Netlist and estimate timing and area parameters

    + 05_Matlab_Software.tar : Software version for training and recognization.

