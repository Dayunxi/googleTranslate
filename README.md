# googleTranslate

调用Google翻译， 每次翻译一行文本
结果以每句话及其对应的翻译呈现

-----

假设原文：
> Salmonella infection triggers multiple inflammatory pathways, suchas stimulationof Toll-like receptor (TLR) signaling via TLR4-mediated sensing of bacterial LPSs as well as recognition of flagellin by TLR5. Furthermore, bacterial peptidoglycan can be sensed via nucleotide-binding and oligomerization domain (NOD) receptors in the host cytosol. Addi-tional evidence further demonstrates that bacterial effector-mediated Rho GTPase activation contributes to NF-kB signaling. Interestingly, our data revealed a prominent increase in numerous ubiquitination sites of linear (methionine (M1)-linked) Ub chain assembly complex (LUBAC) subunits upon infection.

那么返回结果为:
> Salmonella infection triggers multiple inflammatory pathways, suchas stimulationof Toll-like receptor (TLR) signaling via TLR4-mediated sensing of bacterial LPSs as well as recognition of flagellin by TLR5.
> 沙门菌感染引发多种炎症途径，如通过TLR4介导的细菌LPS感染以及通过TLR5识别鞭毛蛋白来刺激Toll样受体（TLR）信号传导。
> Furthermore, bacterial peptidoglycan can be sensed via nucleotide-binding and oligomerization domain (NOD) receptors in the host cytosol.
> 此外，可以通过宿主细胞质中的核苷酸结合和寡聚化结构域（NOD）受体来感测细菌肽聚糖。
> Addi-tional evidence further demonstrates that bacterial effector-mediated Rho GTPase activation contributes to NF-kB signaling.
> 其他证据进一步表明细菌效应物介导的Rho GTP酶激活有助于NF-kB信号传导。
> Interestingly, our data revealed a prominent increase in numerous ubiquitination sites of linear (methionine (M1)-linked) Ub chain assembly complex (LUBAC) subunits upon infection.
> 有趣的是，我们的数据显示，在感染后，线性（甲硫氨酸（M1）连接的）Ub链组装复合物（LUBAC）亚基的多个泛素化位点显着增加。

-----

使用方式：
```dos
python translate.py sourceFile [targetFile]
```
