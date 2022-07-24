# LheF-to-Root
cd  directory containg ExRootAnalysis.
first convert .lhe file to root using "./ExRootLHEFConverter input_name.lhe output_name.root" 
This root file can be analyzed directly or by making its Makeclass in root.
# Install ExRootAnalysis
if you have already Madgraph:

MG5_aMC>install ExRootAnalysis 

else you can install it with

wget http://madgraph.phys.ucl.ac.be/Downloads/ExRootAnalysis/ExRootAnalysis_V1.1.5.tar.gz

tar zxvf ExRootAnalysis_V1.1.5.tar.gz

cd ExRootAnalysis/

make
