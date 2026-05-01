This Jupyter Notebook program generates the geometrically accurate Poincare disk model illustrations appearing in our paper 'Emergence of Minkowski-Spacetime by Simple Deterministic Graph Rewriting' (https://scholar.google.ch/scholar?oi=bibs&cluster=14426533676247745938&btnI=1&hl=en).

Our notebook firstly calculates the coordinates of the points and then uses cduck's hyperbolic library to render the images. 

pip3 install hyperbolic  
pip3 install drawSvg

Here are some examples:

<table>
  <tr>
    <td><img src="generated images/LorentzianTree4.svg" width="500"></td>
    <td><img src="generated images/Lorentzian4Tree8.svg" width="500"></td>
  </tr>
  <tr>
    <td><img src="generated images/LorentzianTree10.svg" width="500"></td>
    <td><img src="generated images/Lorentzian3Tree13.svg" width="500"></td>
  </tr>
</table>
