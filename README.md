<div style="width: 100%; overflow: hidden;">
    <div style="width: 150px; float: left;"> <img src="IMG/logo_IGP.png" alt="Data For Science, Inc" align="left" border="0"> </div>
    <div style="float: left; margin-left: 10px;"> <h1>Assignments</h1>
<h1>Modelado Numérico de la Atmósfera</h1>
        <p>Prof: Dr. Aldo Moya<br/>
        <p>Carlos Enciso Ojeda<br/>
        <a href="https://github.com/carlosenciso/WRF_IGP/">www.atmcenciso.com</a><br/>
            @carlos.enciso.o, senamhi@cenciso</p></div>

<h3>Pressure Total Derivative:</h3>
<div align="center">
<img src="https://render.githubusercontent.com/render/math?math=\frac{DP}{Dt} = \frac{\partial P}{\partial t} %2B u\frac{\partial P}{\partial x} %2B v\frac{\partial P}{\partial y} = 0" width="350"> <br/><br/>
<img src="https://render.githubusercontent.com/render/math?math=\frac{\partial P}{\partial t} = - u\frac{\partial P}{\partial x} - v\frac{\partial P}{\partial y}" width="250"><br/><br/>
<img src="https://render.githubusercontent.com/render/math?math=P_{t+1} = P_{t} - [u\frac{\partial P}{\partial x} - v\frac{\partial P}{\partial y}]\Delta t" width="280"><br/><br/>
</div>

<h3>Results:</h3>
<div align="center">
<img src="FIGs/Presure_advect_HW2_CEO.gif" width="750"/>
</div>
