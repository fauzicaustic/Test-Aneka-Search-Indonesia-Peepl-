START
    INPUT r      // jari-jari
    INPUT t      // tinggi
    
    SET luas_alas_dan_atap = 2 * π * r * r
    SET luas_selimut = 2 * π * r * t
    SET luas_total = luas_alas_dan_atap + luas_selimut
    
    OUTPUT luas_total
END
