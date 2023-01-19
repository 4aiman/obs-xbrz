# obs-xbrz

## OBS XBRz-like shader fIlter

1. get a copy of [obs-shaderfilter](https://github.com/exeldro/obs-shaderfilter/releases) plugin and install it
2. place [files from this repo](./shaders) anywhere on your device
3. add a userdefined shader to your source's filter list
4. select the \*.effect file in the "load from file" 
5. toy with the settings!

## Samples 

Below are some samples from Top Gear 2 for SMD/Genesis with settings applied

### Title Screen
<table width=760px>
    <tr>
        <td> <b>no filter</b> </td>
        <td colspan=2> <b>scalefx-like</b> </td>
    </tr>
    <tr>
        <td> <a href="./img/title_no_filer.png" ><img src="./img/title_no_filer.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/title_scalefx.png" ><img src="./img/title_scalefx.png" width="360"></a> </td>
    </tr>
    <tr>
        <td> no shader </td>
        <td colspan=2> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
    <tr>
        <td> <b>xbrz-like</b> </td>
        <td colspan=2> <b>two-pass</b> </td>
    </tr>
        <td> <a href="./img/title_xbrz.png" ><img src="./img/title_xbrz.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/title_two_pass.png" ><img src="./img/title_two_pass.png" width="360"></a> </td>
    </tr>
    </tr>
        <td> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>First pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>Second pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
</table>
         
         

### Main Menu
<table width=760px>
    <tr>
        <td> <b>no filter</b> </td>
        <td colspan=2> <b>scalefx-like</b> </td>
    </tr>
    <tr>
        <td> <a href="./img/menu_no_filer.png" ><img src="./img/menu_no_filer.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/menu_scalefx.png" ><img src="./img/menu_scalefx.png" width="360"></a> </td>
    </tr>
    <tr>
        <td> no shader </td>
        <td colspan=2> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
    <tr>
        <td> <b>xbrz-like</b> </td>
        <td colspan=2> <b>two-pass</b> </td>
    </tr>
        <td> <a href="./img/menu_xbrz.png" ><img src="./img/menu_xbrz.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/menu_two_pass.png" ><img src="./img/menu_two_pass.png" width="360"></a> </td>
    </tr>
    </tr>
        <td> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>First pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>Second pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
</table>


### Gameplay
<table width=760px>
    <tr>
        <td> <b>no filter</b> </td>
        <td colspan=2> <b>scalefx-like</b> </td>
    </tr>
    <tr>
        <td> <a href="./img/gameplay_no_filer.png" ><img src="./img/gameplay_no_filer.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/gameplay_scalefx.png" ><img src="./img/gameplay_scalefx.png" width="360"></a> </td>
    </tr>
    <tr>
        <td> no shader </td>
        <td colspan=2> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
    <tr>
        <td> <b>xbrz-like</b> </td>
        <td colspan=2> <b>two-pass</b> </td>
    </tr>
        <td> <a href="./img/gameplay_xbrz.png" ><img src="./img/gameplay_xbrz.png" width="360"></a> </td>
        <td colspan=2> <a href="./img/gameplay_two_pass.png" ><img src="./img/gameplay_two_pass.png" width="360"></a> </td>
    </tr>
    </tr>
        <td> 
            <u>Single pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>First pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.25,<br>
            <i>SamplingPointScale:</i> 1.00 
        </td>
        <td> 
            <u>Second pass</u><br> 
            <i>Sharpness:</i> -0.84,<br> 
            <i>StartSmoothingWeight:</i> 1.00,<br> 
            <i>MinFilterWeight:</i> 0.00,<br>
            <i>MaxFilterWeight:</i> 1.00,<br>
            <i>Smoothing:</i> 0.00,<br>
            <i>ScalingFactor:</i> 0.50,<br>
            <i>SamplingPointScale:</i> 0.50 
        </td>
    </tr>
</table>