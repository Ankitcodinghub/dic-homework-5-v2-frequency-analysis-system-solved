# dic-homework-5-v2-frequency-analysis-system-solved
**TO GET THIS SOLUTION VISIT:** [DIC Homework 5 v2-Frequency Analysis System Solved](https://www.ankitcodinghub.com/product/dic-homework-5-v2-frequency-analysis-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93289&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DIC Homework 5 v2-Frequency Analysis System Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
2021 Digital IC Design Homework 5: Frequency Analysis System

1 Introduction

In this homework, you are requested to design a system constructed with a Finite Impulse Response filter (FIR filter), a Fast Fourier Transform (FFT) circuit and an Analysis circuit. This system can filter out the noise with FIR Filter and then transform the signals from time domain into frequency domain with FFT circuit. Finally, the main frequency band of the signal can be found out with Analysis circuit, which can be applied as a sensing system. The functionality of the system will be described in detail in the following parts.

</div>
</div>
<div class="layoutArea">
<div class="column">
2 Design Specifications 2.1 Block overview

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 1 – System block overview.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.2 I/O Interface Name I/O

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Width

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
clk rst

</div>
<div class="column">
I 1 I 1

</div>
<div class="column">
System clock signal. This system is synchronized with the positive edge of the clock.

Active-high asynchronous reset signal.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
data_valid I data I

done O

fir_d O fir_valid O fft_d0 ~ fft_d15 O fft_valid O freq O

</div>
<div class="column">
1 When the host is ready to send data, this signal will be set as high.

16 Time domain signal from the host.

1 When the system complete calculation, this signal

should be set as high.

16 Output data signal of FIR filter.

1 Data valid signal of FIR filter. 32 Output data signal of FFT.

1 Data valid signal of FFT.

4 Output signal for the main frequency.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.3 Function Description

The system gets input time domain signal from the host, the example is shown in figure 2. Then the noise in the input signal is filter out with FIR filter, the filtered result of signal in figure 2 is shown in figure 3.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 2 – Time domain signals from the host.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 3 – Signals which passed the FIR filter.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
After the input signal is filtered and is ready to output, pull up the fir_valid signal. And use fir_d signal to transmit one data in each cycle. The filtered signal will then be processed by FFT, and the frequency domain signal can be obtained. (Take figure 4 as example.) Pull up fft_valid signal and use fft_d signal to transmit one

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
set of data (fft_d0 ~ fft_d15) to the Analysis circuit. When the Analysis circuit complete calculation, pull up done signal and output the main frequency band by freq signal. Among the signals fft_d0 ~ fft_d15, fft_d0 represents the frequency band 0, fft_d1 represents the frequency band 1, and so on.

2.4 Timing Diagram

The timing specification of this design contains four parts: The system timing specification, the input signal timing specification, the FIR output timing specification, and the FFT output timing specification.

2.4.1 System timing specification

The timing diagram in figure 5 shows the system timing specification. After the system is reset, the serial input signals pass FIR filter and output by fir_d serially. Every sixteen output signals from FIR filter will be parallel input to the FFT circuit. The FFT circuit will output the processed signal parallel with signals fft_d0 ~ fft_d15. The Analysis circuit takes these signals and processes them to find the main frequency band. Finally, the main frequency band is output with freq signal. The done signal has to be pulled up at the same time to inform the host that the set of sixteen signals have been processed. The fir_valid, fft_valid, and done signals all maintain as high for 1 cycle for each valid output data. Besides, there is no overlap between any two sets of valid output of FIR filter. For example, the first set of FFT parallel input is constructed with fir_d(0) ~ fir_d(15), and the second set of FFT parallel input will be constructed with fir_d(16) ~ fir_d(31), and so on. In this homework, the host will input 1024 data to the system, so there will be 64 calculation results output by the system.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 4 – Spectrum diagram of signals which are processed by FFT.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 5 – Timing diagram of the system.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.4.2 Input signal timing specification

When the data_valid signal is set as high by the host, the data port will send one data in each cycle. Its timing specification is shown in figure 6. tCYCLE represents the clock width of the system. The width of data signal is 16 bits, which is constructed with a sign bit, 7 bits of integer data, and 8 bits of floating number data. The construction of data is shown in figure 10.

2.4.3 FIR output timing specification

After the signals are filtered with FIR filter, they will be output to the FFT circuit. When the data is transmitting, the fir_valid signal should be set as high. And the testbench will verify the FIR output synchronously. The output timing of FIR filter is shown in figure 7.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 6 – Timing diagram of the host data transmission.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 7 – Timing diagram of FIR output data.

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2.4.4 FFT output timing specification

After the FIR output data are processed with FFT circuit, they will be output to the Analysis circuit. When the data is transmitting, the fft_valid signal should be set as high. And the testbench will verify the FFT output synchronously. The output timing of FFT circuit is shown in figure 8.

2.5 Functionality of FIR filter

The FIR filter in the system is a low pass filter with 32 coefficients, and it is responsible for filtering out the high frequency noise. The coefficients of the filter are fixed, and they are shown in table 2. (They are also stored in the file “FIR_coefficient.dat”.) The first valid output will be calculated after the thirty- second data is input to the FIR filter. Equation 1 shows the calculation process of FIR filter. Figure 9 shows its hardware architecture, and figure 10 shows the format of input data and output fir_d.

𝑁−1

𝑦(𝑛−(𝑁−1))= ∑h(𝑘) 𝑥(𝑛−𝑘) (equation1) 𝑘=0

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 8 – Timing diagram of FFT output data.

</div>
</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 9 – Hardware architecture of FIR filter.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
y(n-(N-1))

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
TABLE. 2 – Coefficients of low pass filter.

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sign bit

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
integer

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
floating number

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 bit 7 bits 8 bits Fig. 10 – Data format (data, fir_d)

2.6 Functionality of FFT circuit

In this system, you are requested to complete a sixteen-point fast Fourier transform. Its hardware architecture is shown in figure 11. The FFT circuit is used to transform the time domain signals into frequency domain signals for following analysis.

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 11 – Hardware architecture of 16-point FFT circuit.

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Figure 12 is an example of the FFT calculation process. The minus sign in the path of fft_b represents the calculation of subtract Y from X, and Wn is the FFT coefficient. The FFT coefficient contains real part (Wn_real) and imaginary part (Wn_imag). To obtain the results, the complex number operations have to be calculated. Figure 13 shows the result of fft_b after the multiplication.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 12 – Example of FFT calculation.

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Real part of fft_b

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Imaginary part of fft_b

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
(a – c)*Wn_real + (d – b)*Wn_imag

(a – c)*Wn_imag + (b – d)*Wn_real Fig. 13 – Multiplication result of fft_b.

The values of FFT coefficients are shown in table 3. The real part coefficients are stored in the file “Real_Value_Ref.dat”, and the imaginary part coefficients are stored in the file “Imag_Value_Ref.dat”. Figure 14 shows the data format of output of FFT circuit (fft_d0 ~ fft_d15).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
TABLE. 3 – Wn coefficients for FFT process.

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Signed bit

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Integer of real part

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Floating number of real part

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Sign bit

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Integer of imaginary part

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Floating number of imaginary part

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 bit 7 bits 8 bits 1 bit 7 bits 8 bits Fig. 14 – Data format (fft_d0 ~ fft_d15).

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Because the output from FIR filter is serial, a serial to parallel circuit has to be designed so that the FFT circuit can meet the timing specification. Figure 15 shows an example of the FFT circuit with the serial to parallel circuit.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig. 15 – 16-point FFT circuit with the serial to parallel circuit.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.7 Functionality of Analysis circuit

After the output of FFT circuit is input, the Analysis circuit has to find out the main frequency band. The definition of main frequency band is: the frequency whose sum of square of the real part data and imaginary part data is maximum. For example, Y(n) = a + bj (n = 0 ~ 15), then a2 + b2 has to be calculated for comparison. Finally, the main frequency band should be output with freq signal. If Y(2) has maximum sum of square, the freq should output 4’b0010.

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
3 Scoring

This homework has two testbench. To get full score, your design must be able to pass the two testbench both. If you just output the golden data without fulfilling the functionality of the system, you will get 0 points.

3.1 Functional Simulation [60%]

The simulation results of FIR output, FFT output, and Analysis results each

account for 20% of score. If all of the results are generated correctly, you will get the following message in ModelSim simulation.

</div>
</div>
<div class="layoutArea">
<div class="column">
3.2

</div>
<div class="column">
Gate Level Simulation [30%] 3.2.1 Synthesis

Your code should be synthesizable. After it is synthesized in Quartus, a file named FAS.vo will be obtained.

3.2.2 Simulation

The simulation results of FIR output, FFT output, and Analysis results each account for 10% of score. If all of the results are generated correctly using FAS.vo, you will get the following message in ModelSim simulation.

Device:Cyclone II EP2C70F896C8

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
3.3 Performance [10%]

The performance is scored by the total logic elements, total memory bit, and

embedded multiplier 9-bit element your design used in gate-level simulation and the simulation time your design takes. The score will be decided by your ranking in all received homework. (The smaller, the better)

Scoring = (Total logic elements + total memory bit + 9*embedded multiplier 9- bit element) × (longest gate-level simulation time in ns)

4 Submission

4.1 Submitted files

You should classify your files into four directories and compress them to .zip

format. The naming rule is HW5_studentID_name.zip. If your file is not named according to the naming rule, you will lose five points.

*.v All of your Verilog RTL code

*.vo Gate-Level netlist generated by Quartus

*.sdo SDF timing information generated by Quartus

4.2 Report file

Please follow the spec of report. If your report does not meet the spec, you may

lose part of score. You are asked to describe how the circuit is designed as detailed as possible, and the flow summary result is necessary in the report. Please fill the fields of total logic elements, total memory bits, and embedded multiplier 9-bit elements according to the flow summary of your synthesized design. And fill the field of gate-level simulation time according to the gate-level simulation result that Modelsim shows.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
RTL category

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Gate-Level category

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Documentary category

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
*.pdf

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The report file of your design (in pdf).

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
4.3 Note

In this homework, you are allowed to modify the defined CYCLE in testbench

file. End_CYCLE, which decides the maximum cycles your circuit took to complete simulation, can also be modified according to your design. Please do not modify any other content of the testbench.

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
