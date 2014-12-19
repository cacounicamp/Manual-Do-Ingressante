import os

env = Environment(ENV = os.environ)

manual = env.PDF(target='manual_do_ingressante.pdf', source="manual_do_ingressante.tex",
                 PDFLATEX='xelatex')
Default(manual)
env.PDF(target='latex.pdf', source="manual_do_ingressante.tex", PDFLATEX='pdflatex')
