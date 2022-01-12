# PDF-Information-Extraction-Benchmark

<!---
## Related Work
![Alt text](./images/rel2.svg)
<img src="./images/rel1.svg">
-->

##
<p float="left" align="center">
<img src="./images/tools.svg" width="700">
 </p>

## Evaluation Framework
<p float="left" align="center">
<img src="./images/EvaluationModel (1).jpg" width="700">
</p>

## Evaluation Metrics
<img src="https://render.githubusercontent.com/render/math?math={\gamma\left( {t}_{e}, {t}_{g} \right) } = 1 -\frac{lev_{{t}_{e},{t}_{g}}(i,j)}{\left| {t}_{e} \right| + \left| {t}_{g} \right|}" width="400">
<img src="https://render.githubusercontent.com/render/math?math=lev_{{t}_{e},{t}_{g}}(i,j)=
\begin{cases} 
    max(i,j), & \text{if $min(i,j)=0$},\\ 
    min \begin{cases}
        lev_{{t}_{e},{t}_{g}}(i-1,j)+1\\
        lev_{{t}_{e},{t}_{g}}(i,j-1)+1\\
        lev_{{t}_{e},{t}_{g}}(i-1,j-1)+1_{({t}_{ei}\neq {t}_{ej})}
    \end{cases}& \text{otherwise}.
\end{cases}" width="400">

## Results
<p float="left" align="center">
          <img src="./images/ref (2).svg" width="400"/>
          <img src="./images/table (2).svg" width="400"/>
</p>
<p float="left" align="center">
<img src="./images/general (2).svg" width="400"/>
<img src="./images/meta (2).svg" width="400"/>
</p>

<p float="left" align="center">
<img src="./images/res1.svg" width="700">
</p>

