tmpdir := tmp

FILES := curriculum.pdf trends.pdf thetool.pdf crash.pdf multi.pdf mpi.pdf \
  	 kongull.pdf openmp.pdf summing.pdf poisson-slides.pdf poisson-solvers.pdf \
	 mpiio_slides.pdf petsc.pdf recap.pdf

all: $(FILES)

$(tmpdir):
	mkdir tmp

curriculum.pdf: | $(tmpdir)
	make -C 00.curriculum

trends.pdf: | $(tmpdir)
	make -C 01.trends

thetool.pdf: | $(tmpdir)
	make -C 02.thetool

crash.pdf: | $(tmpdir)
	make -C 03.crash

multi.pdf: | $(tmpdir)
	make -C 04.multi

mpi.pdf: | $(tmpdir)
	make -C 05.mpi

kongull.pdf: | $(tmpdir)
	make -C 06.kongull

openmp.pdf: | $(tmpdir)
	make -C 07.openmp

summing.pdf: | $(tmpdir)
	make -C 08.sum

poisson-slides.pdf: | $(tmpdir)
	make -C 09.poisson

poisson-solvers.pdf: | $(tmpdir)
	make -C 10.solvers

mpiio_slides.pdf: | $(tmpdir)
	make -C 11.mpi-io

petsc.pdf: | $(tmpdir)
	make -C 12.petsc

recap.pdf: | $(tmpdir)
	make -C 13.recap

clean:
	rm -rf tmp $(FILES)
