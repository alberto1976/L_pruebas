# Bibliografia y Referencias

En este capítulo se presentan las principales características que nos ofrece el paquete bookdown para la gestión de referencias bibliográficas, notas, referencias cruzadas, etc.

## ¿Cómo ingresar una referencia bibliográfica?

Como se presenta en el libro **Cuestión de Supervivencia**[@pinto2007cuestion], la deserción estudiantil 

```markdown
`r if (knitr:::is_html_output()) '# References {-}'`
```

```yaml
---
bibliography: [Referencias/capitulo4.bib]
biblio-style: apalike
link-citations: yes
---
```


```bibtex
@article{pinto2007cuestion,
  title={Cuesti{\'o}n de supervivencia. Graduaci{\'o}n, deserci{\'o}n y rezago en la Universidad Nacional de Colombia},
  author={Pinto, Martha and Dur{\'a}n, D and P{\'e}rez, R and Rever{\'o}n, C and Rodr{\'\i}guez, A},
  journal={Universidad Nacional de Colombia. Direcci{\'o}n Nacional de Bienestar Universitario, Bogot{\'a}},
  year={2007}
}
```



