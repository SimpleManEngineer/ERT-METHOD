# ERT-METHOD
In short the idea is to merge phisical bundles into one secondary bundle that may already have offered traffic (Poisson distribution). Program calculates all necessary parameters for secondary bundle.

functions: <br>
silnia() - calculates factorial of given integer value. <br>
suma() - calculates summ of given integer to the power of 2 divided by factorial of iterating variable. <br>
Erlang() - returns calculated error propability for given arguments. <br>
Secondary_Bundle::find_parameters() - calculates parameters for secondary bundle. <br>
Secondary_Bundle::find_V() - finds the nearest capacity that secondary bundle should have. <br>
Secondary_Bundle::calc_D() - calculates dissemination coefficient for given arguments. <br>
Secondary_Bundle::calc_R() - calculates drifting traffic coefficient from primary bundles based on given arguments. <br>
Secondary_Bundle::disp_parameters() - displays secondary bundle already calculated parameters. <br>

classes: <br>
Primary_Bundle - phisical bundles <br>
Secondary_Bundle - merged phisical bundles <br>

Variables: <br>
A - bitrate <br>
V - capacity <br>
D - dissemination coefficient <br>
R - drifting (flowing down) traffic coefficient <br>
R_sum, D_sum - temporary variables <br>
A_sec - offered trafic (bitrate) for secondary bundle <br>
s - primary bundles pointer table <br>
sec_b - secondary bundle pointer <br>
