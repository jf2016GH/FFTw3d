# FFTw3d
An R wrapper of FFTW 3d tranforms

An example:
  real <- rnorm(1000)
  imag <- rep(0,1000)
  temp <- array(complex(real=real, imaginary=imag), dim=c(10,10,10))
  rfft <- Re.(fftw3d(temp, 0))
