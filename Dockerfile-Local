FROM ipython/scipyserver

RUN mkdir /basis_kurs
WORKDIR /basis_kurs
RUN mkdir ./kurs ./data ./kurs/images

COPY kurs/*.ipynb ./kurs/
COPY kurs/images/*.png ./kurs/images/
COPY data/* ./data/

WORKDIR /basis_kurs/kurs/
