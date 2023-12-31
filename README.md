



```
r language BS30, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis embolizan mikrosferül TR, echo = (language == "TR")
## BS30 - embolizan mikrosferül {#sec-BS30 }
```


```
asis embolisation microspheres EN, echo = (language == "EN")
## BS30 - embolisation microspheres {#sec-BS30 }
```






```
r BS30 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS30-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS30/HE.html",
  file = "./screenshots/BS30-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS30/HE.html](https://images.patolojiatlasi.com/BS30/HE.html)





```
asis, echo = (language == "TR")

**embolizan mikrosferül**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS30-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS30/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS30/HE.html)
```

```
asis, echo = (language == "EN")

**embolisation microspheres**

[![Click for Full Screen WSI](./screenshots/BS30-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS30/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS30/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS30/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS30/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

embolizan mikrosferül

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

embolisation microspheres

:::

```









:::::









