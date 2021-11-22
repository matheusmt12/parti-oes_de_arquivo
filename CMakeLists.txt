cmake_minimum_required(VERSION 3.20)
project(1aEntregaArquivos_zip__Unzipped_Files_ C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(1aEntregaArquivos_zip__Unzipped_Files_
        cliente.c
        cliente.h
        geracao_particoes.c
        geracao_particoes.h
        lista_clientes.c
        lista_clientes.h
        nomes.c
        nomes.h
        test_geracao_particoes.c
        ufftest.h)
