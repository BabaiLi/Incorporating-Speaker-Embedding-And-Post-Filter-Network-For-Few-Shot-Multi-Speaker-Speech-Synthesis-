# Incorporating Speaker Embedding And Post-Filter Network For Few-Shot Multi-Speaker Speech Synthesis System


<b><font size="4">Config:</font></b>
<br>Dataset: AISHELL-3
<br>Training-set: 17,300 Audio, 100 Audio per Speaker (Use 173 Speakers from Dataset)
<br>Iteration: 208,000 (For Four days)
<br>Batch: 8
<br>Vocoder: HiFi-GAN

# Seen Speaker
<br><b> Speaker: SSB0590 </b>
<br><b> Text: 我們不能分頭行動 (wo3 men2 bu4 neng2 fen1 tou2 xing2 dong4)</b>
<div style="border-style:none;width:auto;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/inside/Men/590/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/590/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/590/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/590/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/590/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB0863 </b>
<br><b> Text: 放首歌來聽叮噹的歌 (fang4 shou3 ge1 lai2 ting1 ding1 dang1 de5 ge1)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/inside/Men/863/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/863/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/863/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/863/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Men/863/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB0080 </b>
<br><b> Text: 中新網七月十四日電 (zhong1 xin1 wang3 qi1 yue4 shi2 si4 ri4 dian4)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/inside/Women/80/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/80/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/80/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/80/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/80/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB0470 </b>
<br><b> Text: 畢節市的景點有什麼 (bi4 jie2 shi4 de5 jing2 dian2 you3 shen2 me5)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/inside/Women/470/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/470/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/470/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/470/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/inside/Women/470/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>


# UnSeen Speaker
<br><b> Speaker: SSB1187 </b>
<br><b> Text: 請幫我回到廣西衛視 (qing3 bang1 wo3 hui2 dao4 guang3 xi1 wei4 shi4)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/outside/Men/1187/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB1745 </b>
<br><b> Text: 不斷吸引到用戶的時候 (bu2 duan4 xi1 yin3 dao4 yong4 hu4 de5 shi2 hou4)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/outside/Men/1745/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB0822 </b>
<br><b> Text: 該職位員工可以居住在西雅圖或洛杉磯 (gai1 zhi2 wei4 yuan2 gong1 ke2 yi3 ju1 zhu4 zai4 xi1 ya3 tu2 huo4 luo4 shan1 ji1)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/outside/Women/822/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<br><b> Speaker: SSB1197 </b>
<br><b> Text: 現在你知道百麗兒想要什麼了嗎 (xian4 zai4 ni3 zhi1 dao4 bai3 li4 er2 xiang3 yao4 shen2 mo5 le5 ma5)</b>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th>Target</th>
            <th>
                <audio controls>
                    <source src="audio/outside/Women/1197/gt.wav" type="audio/wav">
                </audio>
            </th>
        </tr>
        <tr>
            <th> </th>
            <th> Post-Filter </th>
            <th> Post-Net </th>
        </tr>
        <tr>
            <td>VC</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>SV</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/sv_pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/sv_pn.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

# Experiment
## How many unseen speaker audio you need that can generate good audio?
<b>
It seems 5~10 Audio will be stability, and 100 Audio is the best.
</b>

<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th> </th>
            <th> Men-1187 </th>
            <th> Men-1745 </th>
        </tr>
        <tr>
            <td>1 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/1187-pf-1.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/1745-pf-1.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>5 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/1187-pf-5.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/1745-pf-5.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>10 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/1187-pf-10.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/1745-pf-10.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>50 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/1187-pf-50.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/1745-pf-50.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>100 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1187/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Men/1745/pf.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th> </th>
            <th> Women-822 </th>
            <th> Women-1197 </th>
        </tr>
        <tr>
            <td>1 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/822-pf-1.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/1197-pf-1.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>5 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/822-pf-5.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/1197-pf-5.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>10 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/822-pf-10.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/1197-pf-10.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>50 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/822-pf-50.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/1197-pf-50.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td>100 Audio</td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/822/pf.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/outside/Women/1197/pf.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

## Diffwave Post-Filter Parameter Fix
<b><font size="4">Original Parameter from the diffwave paper: </font></b>
<br>residual_channels = 64
<br>residual_layers = 30
<br>conv_dilation = 10
<br>parameters = 1.47 MB
<table>
    <tr>
        <td> Audio (broken) </td>
        <td>
            <audio controls>
                <source src="audio/bad/30-64-10.wav" type="audio/wav">
            </audio>
        </td>
    </tr>
</table>

<b><font size="4">Increase the residual_channels </font></b>
<b>
    '''diff
    with -30- residual_layers and -10- conv_dilation
    '''
</b>
<br>We found at least need 192 dim for residual_channels
<br>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th></th>
            <th> Audio </th>
            <th> Parameter </th>
        </tr>
        <tr>
            <td> 128-residual_channels </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/30-128-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 5.22 MB </td>
        </tr>
        <tr>
            <td> 192-residual_channels </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/30-192-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 13.27 MB </td>
        </tr>
    </table>
</div>

<b><font size="4">Reduce the residual_layers </font></b>
<b>with 192-residual_channels and 10 conv_dilation.</b>
<br>We found at least need 10 layers for residual_layers
<br>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th></th>
            <th> Audio </th>
            <th> Parameter </th>
        </tr>
        <tr>
            <td> 30-residual_layers </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/30-192-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 13.27 MB </td>
        </tr>
        <tr>
            <td> 10-residual_layers </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/10-192-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 3.99 MB </td>
        </tr>
        <tr>
            <td> 5-residual_layers </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/5-192-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 2.18 MB </td>
        </tr>
    </table>
</div>

<b><font size="4">Reduce the conv_dilation </font></b>
<b>with 192-residual_channels and 10-residual_layers.</b>
<br>We found more conv_dilation get worse voice quality.
<br>
<div style="border-style:none;width:600;">
    <table>
        <tr>
            <th></th>
            <th> Audio </th>
            <th> Parameter </th>
        </tr>
        <tr>
            <td> 10-conv_dilation </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/10-192-10.wav" type="audio/wav">
                </audio>
            </td>
            <td> 3.99 MB </td>
        </tr>
        <tr>
            <td> 5-conv_dilation </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/10-192-5.wav" type="audio/wav">
                </audio>
            </td>
            <td> 3.99 MB </td>
        </tr>
        <tr>
            <td> 1-conv_dilation </td>
            <td>  
                <audio controls>
                    <source src="audio/bad/10-192-1.wav" type="audio/wav">
                </audio>
            </td>
            <td> 3.99 MB </td>
        </tr>
    </table>
</div>

<b> Final parameter setting for our TTS Model: </b>
<br>residual_channels = 192
<br>residual_layers = 10
<br>conv_dilation = 1
<br>parameters = 48.1 MB
<br>
<br> *Notice: Post-Net's parameters = 4.35 MB
