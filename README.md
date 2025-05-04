# NASSCOM-Semiconductor-Packaging
The repository is about the semiconductor packaging workshop offered by VSD and NASSCOM.
It contains the details about the labs and exploring other packages.


The activities include:
<div class="toc">
  <ul>
    <li><a href="#header-1">Semiconductor Packaging</a></li>
  </ul>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-2">Lab-1 Thermal Analysis</a></li>
  </ul>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-3">Lab-2 Package Design and Modeling</a></li>
  </ul>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-6">Acknowledgements</a></li>
  </ul>
</div>  


## <h2 id="header-1">Semiconductor Packaging</h2>

![image1](https://github.com/user-attachments/assets/7e5e9292-ca7c-408b-bb15-689e49ecf89f)

![image2](https://github.com/user-attachments/assets/cbe4ecca-76da-4edf-ba62-a27939809a12)

![image3](https://github.com/user-attachments/assets/ccf83158-bd49-4e6c-9516-6e2d921155bb)

![image4](https://github.com/user-attachments/assets/53b01a0d-780e-4d3a-ac7d-aad4da460c04)

![image5](https://github.com/user-attachments/assets/ee8bdb43-80c6-4162-9e63-861bf12503fd)

![image6](https://github.com/user-attachments/assets/ce4be847-d1be-4866-8336-a77c43e33bdb)

![image7](https://github.com/user-attachments/assets/4860aaff-7e1f-4942-8ebf-fd03ec3b6e32)

![image8](https://github.com/user-attachments/assets/ce924e9c-742a-435b-84c0-f85df99802b2)

![image9](https://github.com/user-attachments/assets/44b58333-e686-4d6a-8901-de239873be07)

![image10](https://github.com/user-attachments/assets/18f589ff-fb02-4748-ae93-abb5da4ce45c)

![image11](https://github.com/user-attachments/assets/32e0454d-040c-4cfb-89b1-10c48476e6f5)

![image12](https://github.com/user-attachments/assets/be225f4a-4d86-4085-a066-cf679496ce22)

![image13](https://github.com/user-attachments/assets/a7e43718-0866-43ca-8634-ad88a505b055)

![image14](https://github.com/user-attachments/assets/ae0f45c1-cb84-441f-a9b7-46ddbbf79818)



---------------------------------------------------------------------------------------------------------------------------
## <h2 id="header-2">Lab-1 Thermal Analysis</h2>


Open Ansys Electronics Desktop. Go to Project -> Insert Icepack Design
![image15](https://github.com/user-attachments/assets/894e8182-10fd-4b15-911a-30880c901f67)


![image16](https://github.com/user-attachments/assets/0cd945d1-109f-4a80-94f2-7813d385b0d3)

![image17](https://github.com/user-attachments/assets/aac7707e-f23f-47a0-a9f8-c6f4ec2ccc7f)

![image18](https://github.com/user-attachments/assets/e5d8563c-f988-4d23-9de0-eb3abcfe6002)

![image19](https://github.com/user-attachments/assets/86171dae-dee3-4260-97cb-013c9e2d4c74)

![image20](https://github.com/user-attachments/assets/cba1cae6-e214-4b99-8569-e026919293f8)

![image21](https://github.com/user-attachments/assets/03773c00-83ee-44bc-a785-bf9fe0fb4fa0)

![image22](https://github.com/user-attachments/assets/807bdf49-70d2-4cde-990d-c22395b71726)

![image23](https://github.com/user-attachments/assets/3cea8145-f189-44c1-b208-f5a6c386309a)
Remove unnecessary elements (e.g., Flipchip_BGA_trace1 under Thermal)
Assign temperature monitors to undefil, substrate and die
![image24](https://github.com/user-attachments/assets/0c482ed4-1a14-4a54-987e-d481b32c4d01)

![image25](https://github.com/user-attachments/assets/71a91b86-2e14-4eb4-9f6f-7fca335133ec)

![image26](https://github.com/user-attachments/assets/e26d8d81-3a42-4074-af89-4ee2062ce61b)

![image27](https://github.com/user-attachments/assets/60d6f9cb-19ed-440d-8671-44e0f6f01d3b)

![image28](https://github.com/user-attachments/assets/3e7b3898-3499-4d73-9099-d4fe704b6708)

![image29](https://github.com/user-attachments/assets/32338dfc-1397-4c8c-bec8-9d60ce989cbb)

![image30](https://github.com/user-attachments/assets/11608af7-a7f5-4dd5-8730-c825c069c887)

![image31](https://github.com/user-attachments/assets/4a79e499-7936-4b54-a7eb-1d391cfd24f3)

Similarly, we can do thermal analysis for other packages. Below is the image for the QFN package.
![image32](https://github.com/user-attachments/assets/3f5a3a32-2825-41f0-9297-0999976d2203)

----------------------------------------------------------------------------------------------------------------------------
## <h2 id="header-3">Lab-2 Package Design and Modeling</h2>

![image33](https://github.com/user-attachments/assets/ffce76a0-14c5-4acd-9efa-dbf3de40a7f9)
Create a rectangle of size 2.05 x 1.4 mm. And put the location as origin (0,0,0)
![image34](https://github.com/user-attachments/assets/1e7baa6e-fa70-414f-9a1e-38b6fcd2868e)
Select the rectangle and proceed as per the image, and select the Thicken sheet function
![image35](https://github.com/user-attachments/assets/866b4cba-d319-490f-87c4-d6e6edae4120)
And provide the die thickness as the value. In our case, we have used 0.3mm as die height.
![image36](https://github.com/user-attachments/assets/9221c5d3-8269-4ca1-b7aa-483e308197d6)

Change the name of the rectangle to Die. And select the materials as die material or silicon in our case.
![image37](https://github.com/user-attachments/assets/c1620c62-6907-45bf-aa21-5b8392c74a54)

Create another rectangle with dimensions shown below:
![image38](https://github.com/user-attachments/assets/e268c37c-b5a6-4f1a-b1b1-c4c7d2e431d3)
The thickness we have used is a negative value, so that it expands downward. 
![image39](https://github.com/user-attachments/assets/c23e2fb4-40e7-40b0-b808-5fd89ef5efe2)
Change the name of the rectangle to Substrate and select the material as FR4.
![image40](https://github.com/user-attachments/assets/41e44c95-e4db-4767-8c19-0b0d4eb7958c)
Create a same size rectangle as Die with the same location. Only add thickness as -0.1 to fill the gap between the die and the substrate.
![image41](https://github.com/user-attachments/assets/da11d9eb-b72a-4b51-9a8f-4a55c638c5cd)
Change the rectangle name to Dieattach and the material to modified epoxy
![image42](https://github.com/user-attachments/assets/abddd113-2929-4bab-82fb-6a302975ce95)
The highlighted portion is the Die attach portion.
![image43](https://github.com/user-attachments/assets/24910d2d-d6fc-45fd-9f84-b23c83dd14b9)
Create a rectangle on the die that will look like the figure below.
![image44](https://github.com/user-attachments/assets/91fea646-f8c2-4a65-87a0-547c24f7fbd4)
Values for the pad and size are given in the image below.
![image45](https://github.com/user-attachments/assets/ee5d0dc2-0231-4b15-b870-14f8b585c09c)
Add thickness to the rectangle by selecting a function from Modeler>Surface>Thicken Sheet. Add thickness approx 50 micron.
![image46](https://github.com/user-attachments/assets/cab98a6a-af9e-426a-b43e-1cbb791a2112)
Change the rectangle name to Diebondpad and the material to copper or any other conductive material as per the customer's requirement. Here I have changed the colour to dark yellow to look like copper. 
![image47](https://github.com/user-attachments/assets/25f011fd-d5ac-4f00-921c-c55f23b3b2f1)
Place 3 more rectangles at a pitch of 0.45 mm.
In the same manner, place 4 more rectangles on the opposite side. The figure below shows the position of one of the opposite side diebondpad 
![image48](https://github.com/user-attachments/assets/48cdf452-bc80-4f12-a752-224763e19900)
After placing all the rectangles, change the rectangle name and material similar to diebondpad.

Create a rectangle on the substrate 
![image49](https://github.com/user-attachments/assets/c27d2ed6-486d-45ce-9acf-6efc013362d4)

The size and position of the reactangle are shown in the figure below
![image50](https://github.com/user-attachments/assets/4769c989-f0ec-48b9-b366-58b1c6ed5b44)

Add thickness
![image51](https://github.com/user-attachments/assets/ee1ea2be-51d6-46d2-8e80-471fad7d30d4)

change the rectangle name, material and color
![image52](https://github.com/user-attachments/assets/7f63aba7-f7af-4b35-b92b-320df0414984)

After placing a few more rectangles at a pitch of 0.5 mm, and repeating the same process of name and material. The final image will look like this.
![image53](https://github.com/user-attachments/assets/e816b391-2ee5-4706-a736-0bf0d3148d21)

Click on draw button and select the bondwire function. Joint to diebondpad and substartebondpad using bondwire function.
![image54](https://github.com/user-attachments/assets/9e4e32ed-3876-4e49-ae7f-a13a4ad3caab)

Change the name and material if required
![image55](https://github.com/user-attachments/assets/49f72404-d9a7-4b11-83f0-87ba384d1bd3)

After connecting all the connection, the die will look like below
![image56](https://github.com/user-attachments/assets/30271c97-251c-4879-8118-0d900b37016a)

Create a rectangle of the same size and location as the substrate. And add Thickness 0.9 mm.
![image57](https://github.com/user-attachments/assets/4c817e2e-b0da-4026-8e31-c7d343099512)

Change the rectangle name to Moldedbody and the material to epoxy or similar material
![image58](https://github.com/user-attachments/assets/d8160648-911c-4ae9-93fc-d96c0a313543)

Final model of DFN package will look like the image below
![image59](https://github.com/user-attachments/assets/84c8b8ee-53e2-4009-8e6f-e081e3a3269f)
![image60](https://github.com/user-attachments/assets/7faee64d-99e6-408b-9bb7-079da7899b04)


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  
## <h2 id="header-6">Acknowledgements</h2>
 
[Dr. Tarun Kumar Agarwal](https://iitgn.ac.in/faculty/ee/fac-tarun)
[Kunal Ghosh](https://github.com/kunalg123) 
