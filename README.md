# lib_digitales
int cantidad_pasos_tilt(int  grados_tilt) {

  int factor_reduccion = 7;
  float grados_por_pasos = 1.8;

  int total_grados_tilt = grados_tilt * factor_reduccion;

  int total_pasos_tilt = total_grados_tilt / grados_por_pasos;

  return total_pasos_tilt;

}

int cantidad_pasos_pan(int grados_pan) {

  int factor_reduccion = 7;
  float grados_por_pasos = 1.8;


  int total_grados_pan = grados_pan * factor_reduccion;

  int total_pasos_pan = total_grados_pan / grados_por_pasos;

  return total_pasos_pan;

}
