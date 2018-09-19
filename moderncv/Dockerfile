FROM gocho/latex:latest

MAINTAINER Guillaume Lhermenier <guillaume.lhermenier@gmail.com>

WORKDIR /usr/share/texmf/tex/latex

CMD apt-get install -y unzip \
	&& wget http://mirrors.ctan.org/macros/latex/contrib/moderncv.zip \
	&& unzip moderncv.zip \
	&& rm -f modercv.zip


