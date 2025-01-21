# HYG STAR MAP
- [THIS PROJECT WAS BUILT UPON https://github.com/EnguerranVidal/HYG-STAR-MAP
<img src="https://user-images.githubusercontent.com/80796115/112481174-05a11700-8d77-11eb-8a1b-f5fc7d1f8d03.PNG" width="500" height="500">

 This project's goal is to create a 3D Star map from HYG ( Hypparcos satellite star survey ) data as well as eventually create a HR diagramm and other pretty plots.
 The code currently supports a Hertzsprung-Russell diagram plot as well as a 3D "bubble" function able to plot the stars around the Sun situated under a certain distance from it. This code works with CSV, NUMPY, FLASK, JSON, PLOTLY and MATPLOTLIB.PYPLOT. Please try getting a working environment with these libraries implemented before attempting to run it. The following code and content is copyrighted under the MIT License ( for further details see [License.md](https://github.com/EnguerranVidal/HYG-STAR-MAP/blob/main/License.md) ).
 

## HYG DATA FORMAT :

If we look at the **[hygdatav3.txt](https://github.com/EnguerranVidal/HYG-STAR-MAP/blob/main/hygdatav3.txt)**, these are the labels :

**id,hip,hd,hr,gl,bf,proper,ra,dec,dist,pmra,pmdec,rv,mag,absmag,spect,ci,x,y,z,vx,vy,vz,rarad,decrad,pmrarad,pmdecrad,bayer,flam,con,comp,comp_primary,base,lum,var,var_min,var_max**

Among the labels, we mainly use "id", "hip", "hd", "hr", "gl", "bf" and "proper" to name the stars in each plots but also "x", "y", "z", "distance", "ci", "absmag" and "lum" in the HR diagram and space bu
bubble layouts.

## HOW TO RUN : 

- After pulling from github open up your terminal and download the requirements.txt file (pip install -r /path/to/requirements.txt)
- Make sure your virtualenv is running and type this command in the terminal : python3 main.py  (source ./yourENV/bin/activate)
- This will open up local host in your browser and you can now access the website
- This will become an actual website in the future.
