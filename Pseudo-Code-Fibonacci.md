FUNCTION fibonacci(n)
    IF n <= 1 THEN
        RETURN n
    ELSE
        RETURN fibonacci(n - 1) + fibonacci(n - 2)
    ENDIF
END FUNCTION


START
    INPUT n    // jumlah deret Fibonacci
    
    OUTPUT "Deret Fibonacci hingga", n, "adalah:"
    
    FOR i = 0 TO n - 1 DO
        OUTPUT fibonacci(i)
    ENDFOR
END
