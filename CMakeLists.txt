project(raytracing)

set(CMAKE_CXX_FLAGS_RELEASE)

add_executable(raytracing 
  vec3.h
  camera.h
  color.h
  hittable.h
  hittable_list.h
  interval.h
  material.h
  ray.h
  rt_types.h
  sphere.h
  vec3.h
  main.cc
)
