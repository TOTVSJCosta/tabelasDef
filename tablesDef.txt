ZZ1 - Cadastro de Integrações
X3_CAMPO      X3_TITULO      X3_TIPO  X3_TAMANHO  X3_RELACAO                  X3_CBOX
----------    -------------  -------  ----------  --------------------------  --------------------------------------
ZZ1_ID        ID Integração  C        3           GETSX8NUM("ZZ1", "ZZ1_ID")
ZZ1_FINALI    Finalidade     C        50
ZZ1_STATUS    Status         C        1                                        H=Habilitada;D=Desabilitada
ZZ1_METODO    Método         C        1                                        A=Arquivo;G=GET;P=POST;U=PUT;D=DELETE
ZZ1_URL       Host           C        50
ZZ1_FUNCAO    Pto Entrada    C        8

ZZ2 - Histórico das Integrações
X3_CAMPO      X3_TITULO      X3_TIPO  X3_TAMANHO  X3_RELACAO                  X3_CBOX
----------    -------------  -------  ----------  --------------------------  --------------------------------------
ZZ2_ID        Log ID         C        10          GETSX8NUM("ZZ2", "ZZ2_ID")
ZZ2_STATUS    Status         C        1                                        S=Sucesso;E=Erro
ZZ2_DATAEX    Método         C        1                                        A=Arquivo;G=GET;P=POST;U=PUT;D=DELETE
ZZ2_HORAEX    Host           C        50
ZZ2_TASKID    Pto Entrada    C        8
ZZ2_RESULT    Resultado      M
