message ( STATUS "Tutorial SENSEI Particles_NeighborList .... enabled")

set(_sources CheckPair.H Constants.H main.cpp MDParticleContainer.cpp MDParticleContainer.H)
set(_input_files inputs sensei)

setup_tutorial(_sources _input_files
  BASE_NAME Particles_NeighborList)

unset(_sources)
unset(_input_files)
