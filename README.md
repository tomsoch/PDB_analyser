# PDB_analyser
The Protein Data Bank (PDB) is a database for the three-dimensional structural data of large biological molecules, such as proteins and nucleic acids.

Script:
1. Downloads any PDB file containing the protein to a directory on the Google Drive, based on the code provided by the user;
2. Filters out the temperature factors for Cα atoms of the A chain along with the numbers of amino acid residues
3. Counts the range of temperature factors (minimum and maximum), mean and standard deviation
4. Asks the user to enter a threshold that will be used to filter out the highest temperature factors, and then prints the numbers of residues for which the temperature factors of Cα (CA) atoms are above the given threshold,
5. Plots the values of temperature factors for Cα atoms as a function of the residue number and marks the values of temperature factors higher than the threshold specified by the user.

Exemplary plot for 1lys:

![image](https://user-images.githubusercontent.com/73905822/115399928-fb90fd80-a1e8-11eb-954f-e4dc1c0a3783.png)
