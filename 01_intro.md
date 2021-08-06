# (PART) Introduction {-}

# Introduction {#introduction}

<script>
document.addEventListener("click", function (event) {
    if (event.target.classList.contains("rebook-collapse")) {
        event.target.classList.toggle("active");
        var content = event.target.nextElementSibling;
        if (content.style.display === "block") {
            content.style.display = "none";
        } else {
            content.style.display = "block";
        }
    }
})
</script>

<style>
.rebook-collapse {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.rebook-content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>


## Community

This resource is a result of a community-driven development process
that has emerged over the past decade. The community is open, and you can best find us and join us through the following channels:

 - [Bioconductor Slack](https://bioc-community.herokuapp.com/) channel #miaverse
 - [Gitter / Matrix](https://gitter.im/microbiome/miaverse) channel #miaverse
 - Project homepage at [microbiome.github.io](microbiome.github.io)

You are also welcome to contact the key developers directly.


## Acknowledgements

This work would not have been possible without the countless
contributions and interactions within the broader research
community. In particular, we express our gratitude to the entire
Bioconductor community for developing this high-quality open research
software repository for life science analytics, continuously pushing
the limits in emerging application fields.

The miaverse framework has drawn inspiration from many sources, most
notably from the work on _phyloseq_ by Paul McMurdie and Susan Holmes
[@McMurdie2013] who pioneered the work on reproducible microbiome data
science in R/Bioconductor. The phyloseq framework continues to provide
a strong of complementary packages and methods in this field, and we
thrive to support full interoperability. Open source books by Susan
Holmes and Wolfgang Huber, Modern Statistics for Modern Biology
[@Holmes2019] and by Garret Grolemund and Hadley Wickham, the R for
Data Science [@Grolemund2017], and Richard McElreath's Statistical
Rethinking and the associated online resources by Solomon Kurz
[@McElreath2020] are key references that advanced reproducible data
science training and dissemination. Finally, the Orchestrating
Single-Cell Analysis with Bioconductor, or _OSCA_ book by Robert
Amezquita, Aaron Lun, Stephanie Hicks, and Raphael Gottardo
[@Amezquita2020] has carried out closely related work on the
_SummarizedExperiment_ data container and its derivatives in the field
of single cell sequencing studies. Many methods and approached used in
this book have been derived from the OSCA framework, with the
necessary further adjustments for microbiome research.

The miaverse framework is based on the _TreeSummarizedExperiment_ data
container created by Ruizhu Huang and others
[@R-TreeSummarizedExperiment], and the idea of using this as an
upgraded basis for microbiome research was initially advanced by the
groundwork of Domenick Braccia, Héctor Corrada Bravo, and
[others](https://github.com/microbiome/mia/blob/master/DESCRIPTION). When
this was brought together with the background work of Felix Ernst, Leo
Lahti and Sudarshan Shetty on complementary aspects of microbiome data
science, the miaverse community gradually started to gather
momentum. Other key contributors include Tuomas Borman, Henrik
Eckermann, Chandler Ross, and Chouaib Benchraka, additional [pull
requests](https://github.com/microbiome/OMA/graphs/contributors),
[issues](https://github.com/microbiome/OMA/issues), and other work in
the background.












