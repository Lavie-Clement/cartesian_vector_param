# CMakeList.txt : projet CMake pour Cartesian_vector_param, incluez la source et définissez
# la logique spécifique au projet ici.
#
cmake_minimum_required (VERSION 3.8)
project(MyFirstProg)
# Ajoutez une source à l'exécutable de ce projet.
add_executable (Cartesian_vector_param "main.cpp" "Vector.hh" "Vector.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Cartesian_vector_param PROPERTY CXX_STANDARD 20)
endif()

# TODO: Ajoutez des tests et installez des cibles si nécessaire.
