object Form1: TForm1
  Left = 1356
  Top = 148
  Width = 1744
  Height = 699
  Caption = 'Combine Bind Variable'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  OldCreateOrder = False
  OnShow = FormShow
  PixelsPerInch = 96
  TextHeight = 13
  object Label1: TLabel
    Left = 16
    Top = 104
    Width = 21
    Height = 13
    Caption = 'SQL'
  end
  object Label2: TLabel
    Left = 24
    Top = 304
    Width = 36
    Height = 13
    Caption = 'Param1'
  end
  object Label3: TLabel
    Left = 16
    Top = 408
    Width = 36
    Height = 13
    Caption = 'Param2'
  end
  object Label4: TLabel
    Left = 24
    Top = 448
    Width = 30
    Height = 13
    Caption = 'Merge'
  end
  object Label5: TLabel
    Left = 720
    Top = 432
    Width = 66
    Height = 13
    Caption = 'bind variable1'
  end
  object Label6: TLabel
    Left = 880
    Top = 432
    Width = 72
    Height = 13
    Caption = 'vbind variable2'
  end
  object Memo1: TMemo
    Left = 80
    Top = 96
    Width = 969
    Height = 177
    ImeName = 'Microsoft IME 2010'
    Lines.Strings = (
      'SELECT  DISTINCT'
      #13#10#10
      ''
      ''
      ''
      ''
      ''
      ''
      
        #9#9#9#9'        DECODE( cast( ? as VARCHAR(#)), '#39'$'#39', '#39'$'#39', x.p_name |' +
        '| x.p_no ) AS SORT_GB1,'#10#9#9#9#9'        x.P_NAME || x.P_NO AS SORT_G' +
        'B2,'#10#9#9#9#9'        y.DEPT_CODE,'#10#9#9#9#9'        y.SRV_SITTN_SNO,'#10#9#9#9#9'  ' +
        '      y.SRV_SITTN_BFR_SNO,'#10#9#9#9#9'        y.SRV_SITTN_CODE,'#10#9#9#9#9'   ' +
        '     SP_CM_CDTRFO02_FU('#39'$'#39',y.SRV_SITTN_CODE) AS SRV_SITTN_CODE_N' +
        'M ,'#10#9#9#9#9'        x.P_NO,'#10#9#9#9#9'        x.P_NAME,'#10#9#9#9#9'        x.REQS' +
        'T_TTM_DEPT_CODE,'#10#9#9#9#9'        SP_CM_CDTRFO05_FU(x.REQST_TTM_DEPT_' +
        'CODE) as REQST_DEPT_NM, --?'#10#9#9#9#9'         x.DEPT_ABRV_NM, --'#10#9#9#9#9 +
        '        x.CLSS_NM,'#10#9#9#9#9'        SP_CM_CDTRFO02_FU('#39'$'#39',x.P_COP_COD' +
        'E) P_COP_NM,'#10#9#9#9#9'        y.BEGIN_YMD,'#10#9#9#9#9'        y.BEGIN_HM,'#10#9#9 +
        #9#9'        y.END_YMD,'#10#9#9#9#9'        y.END_HM,'#10#9#9#9#9'        SUBSTR(y.' +
        'BEGIN_YMD, #,#) || '#39'$'#39' || SUBSTR(y.BEGIN_YMD, #,#) || '#39'$'#39' || SUB' +
        'STR(y.BEGIN_YMD, #,#)'#10#9#9#9#9'            ||'#39'$'#39'|| SUBSTR(y.BEGIN_HM,' +
        '#,#) || '#39'$'#39' ||SUBSTR(y.BEGIN_HM,#,#)'#10#9#9#9#9'            ||'#39'$'#39'||'#10#9#9#9 +
        #9'            SUBSTR(y.END_YMD, #,#) || '#39'$'#39' || SUBSTR(y.END_YMD, ' +
        '#,#) || '#39'$'#39' || SUBSTR(y.END_YMD, #,#)'#10#9#9#9#9'      '
      
        '      ||'#39'$'#39'|| SUBSTR(y.END_HM,#,#) || '#39'$'#39' ||SUBSTR(y.END_HM,#,#)' +
        '   AS SRV_SITTN_PRD,'#10#9#9#9#9'        y.SRV_SITTN_DD_SMTOT,'#10#9#9#9#9'     ' +
        '   CASE  WHEN NVL(y.SRV_SITTN_DD_SMTOT,#)  > #'#10#9#9#9#9'             ' +
        ' THEN DECODE(y.SRV_SITTN_TM_SMTOT, # , DECODE(y.SRV_SITTN_MM_SMT' +
        'OT, #, TO_CHAR(y.SRV_SITTN_TM_SMTOT),'#10#9#9#9#9'                      ' +
        '                                                           DECOD' +
        'E(y.DD_RPAT_YN,'#39'$'#39','#39'$'#39','#39'$'#39')  )'#10#9#9#9#9'                             ' +
        '                 , DECODE(y.DD_RPAT_YN,'#39'$'#39','#39'$'#39','#39'$'#39')  || y.SRV_SI' +
        'TTN_TM_SMTOT )'#10#9#9#9#9'              ELSE TO_CHAR(y.SRV_SITTN_TM_SMT' +
        'OT) END AS SRV_SITTN_TM_SMTOT,'#10#9#9#9#9'        y.SRV_SITTN_MM_SMTOT,' +
        #10#9#9#9#9'        y.SRV_SITTN_RSN || DECODE(y.TRVCT_PYRFL_YN, '#39'$'#39', '#39'$' +
        #39', '#39'$'#39') AS SRV_SITTN_RSN,'#10#9#9#9#9'        y.DESTI_NM,'#10#9#9#9#9'        y.' +
        'OFFL_VHCLE_UTILZ_YN,'#10#9#9#9#9'        y.TRVCT_PYRFL_YN,'#10#9#9#9#9'        y' +
        '.DESTI_OTHBC_YN,'#10#9#9#9#9'        y.PRD_OTHBC_YN,'#10#9#9#9#9'        y.ADP_I' +
        'NSTT_REQST_YN,'#10#9#9#9#9'        y.DD_RPAT_YN,'#10#9#9#9#9'        y.DELT_YN,'#10 +
        #9#9#9#9'        DECODE(y.DELT_YN, '#39'$'#39',  '#39'$'#39', '#39'$'#39') DELT_YN_NM,'#10#9#9#9#9'  ' +
        ' '
      
        '     y.SANC_DOCT_DELT_YN,'#10#9#9#9#9'        y.EMGNC_CNCT_TELNO,'#10#9#9#9#9'  ' +
        '      x.SRVIC_PESN_SC_CODE,'#10#9#9#9#9'        y.UPDID,'#10#9#9#9#9'        y.C' +
        'ONFM_STTUS_CODE as CONFM_STTUS_CODE_ORG ,'#10#9#9#9#9'        DECODE(y.C' +
        'ONFM_STTUS_CODE, '#39'$'#39',  DECODE(y.SANC_DOCT_DELT_YN, '#39'$'#39', '#39'$'#39', y.C' +
        'ONFM_STTUS_CODE), y.CONFM_STTUS_CODE) as CONFM_STTUS_CODE , --  ' +
        '  ?'#10#9#9#9#9'        DECODE(y.CONFM_STTUS_CODE, '#39'$'#39', '#39'$'#39#10#9#9#9#9'        ' +
        '                         , '#39'$'#39', '#39'$'#39#10#9#9#9#9'                        ' +
        '         , '#39'$'#39', DECODE(y.SANC_DOCT_DELT_YN, '#39'$'#39', '#39'$'#39', SP_CM_CDTR' +
        'FO02_FU('#39'$'#39', y.CONFM_STTUS_CODE))'#10#9#9#9#9'                          ' +
        '       , SP_CM_CDTRFO02_FU('#39'$'#39', y.CONFM_STTUS_CODE) ) AS CONFM_S' +
        'TTUS_CODE_NM,'#10#9#9#9#9'        NVL((SELECT DISTINCT '#39'$'#39' FROM TN_SRVSE' +
        'RWS001 WHERE DEPT_CODE = y.DEPT_CODE AND SRV_SITTN_BFR_SNO = y.S' +
        'RV_SITTN_SNO ), '#39'$'#39' ) AS CANCL_YN,'#10#9#9#9#9'       (SELECT SP_CM_DEC_' +
        'FU(USER_NM_ENCPT) FROM TN_SYMUSMUM001 WHERE USRID = Y.UPDID) AS ' +
        'DRA_NM'#10#9#9#9#9'  from ('#10#9#9#9#9'        select  ws02.*, sm03.SRVIC_PESN_' +
        'SC_CODE, sm03.gb, sm03.DEPT_ABRV_NM, sm03.CLSS_NM, sm03.COP_CODE' +
        ' '
      
        'P_COP_CODE'#10#9#9#9#9'          from'#10#9#9#9#9'                ( SELECT P_NO,' +
        ' '#39'$'#39' GB, DEPT_ABRV_NM, CLSS_NM, SRVIC_PESN_SC_CODE, COP_CODE'#10#9#9#9 +
        #9'                  FROM   TN_SRVSERSM003'#10#9#9#9#9'                  W' +
        'HERE  ( DEPT_CODE = ? AND     HFFC_STTUS_CODE IN ('#39'$'#39', '#39'$'#39', '#39'$'#39',' +
        ' '#39'$'#39', '#39'$'#39', '#39'$'#39', '#39'$'#39', '#39'$'#39', '#39'$'#39')'#10#9#9#9#9'                         )'#10#9#9 +
        #9#9'                  OR     ( NVL(ORGN_PSITN_DEPT_CODE, ORGN_AOC)' +
        ' = ? AND  HFFC_STTUS_CODE = '#39'$'#39' AND    SRVIC_PESN_SC_CODE IN ('#39'$' +
        #39','#39'$'#39') )'#10#9#9#9#9'                  UNION'#10#9#9#9#9'                  SELEC' +
        'T P_NO, '#39'$'#39' GB , DEPT_ABRV_NM, CLSS_NM, SRVIC_PESN_SC_CODE,COP_C' +
        'ODE'#10#9#9#9#9'                  FROM   TN_SRVSERSM003'#10#9#9#9#9'            ' +
        '      WHERE  P_NO IN (  SELECT P_NO'#10#9#9#9#9'                        ' +
        '            FROM   TN_SRVSERWS002'#10#9#9#9#9'                          ' +
        '          WHERE  REQST_TTM_DEPT_CODE = ?'#10#9#9#9#9'                   ' +
        '                 AND    END_YMD   >=  ?'#10#9#9#9#9'                    ' +
        '                AND    BEGIN_YMD <=  ?'#10#9#9#9#9'                     ' +
        '            )'#10#9#9#9#9'                 ) SM03'#10#9#9#9#9'                ,T'
      
        'N_SRVSERWS002 WS02'#10#9#9#9#9'        where ws02.P_NO = sm03.P_NO'#10#9#9#9#9' ' +
        '       and   ( GB = '#39'$'#39' OR ( GB = '#39'$'#39' AND REQST_TTM_DEPT_CODE = ' +
        ' ? ))'#10#9#9#9#9'        ) x'#10#9#9#9#9'        , TN_SRVSERWS001 y'#10#9#9#9#9'where y' +
        '.DEPT_CODE     = CAST(x.DEPT_CODE     AS VARCHAR(#))'#10#9#9#9#9'  and y' +
        '.SRV_SITTN_SNO = CAST(x.SRV_SITTN_SNO AS DECIMAL(#))'#10#9#9#9#9'  AND y' +
        '.END_YMD   >= ?'#10#9#9#9#9'  AND y.BEGIN_YMD <= ?'#10#9#9#9#9'  AND y.CONFM_STT' +
        'US_CODE != '#39'$'#39#10#9#9#9#9'  AND NOT ( NVL(y.DELT_YN, '#39'$'#39') = '#39'$'#39#10#9#9#9#9'   ' +
        '         AND    y.CONFM_STTUS_CODE NOT IN ('#39'$'#39', '#39'$'#39')'#10#9#9#9#9'       ' +
        '   )'#10#9#9#9#9'   AND  y.SRV_SITTN_CODE LIKE ? ||'#39'$'#39#10#9#9#9#9#9#9#9#9'AND   y.C' +
        'ONFM_STTUS_CODE LIKE ? || '#39'$'#39#10#9#9#9#9#9#9#9#9'  AND  x.P_NO LIKE ? ||'#39'$'#39 +
        #10#9#9#9#9'  AND   not exists (select #'#10#9#9#9#9'                    from  ' +
        ' TN_SRVSERWS001 z'#10#9#9#9#9'                    where  DEPT_CODE      ' +
        '            = y.dept_code'#10#9#9#9#9'                    and    SRV_SIT' +
        'TN_BFR_SNO          = y.SRV_SITTN_SNO'#10#9#9#9#9'                    an' +
        'd exists (SELECT #'#10#9#9#9#9'                                FROM TN_S' +
        'RVSERWS002'#10#9#9#9#9'                                WHERE P_NO       ' +
        ' '
      
        '  = x.P_NO'#10#9#9#9#9'                                AND DEPT_CODE    ' +
        ' = z.dept_code'#10#9#9#9#9'                                AND SRV_SITTN' +
        '_SNO = z.SRV_SITTN_SNO )'#10#9#9#9#9'                    and y.CONFM_STT' +
        'US_CODE NOT IN ('#39'$'#39', '#39'$'#39') )'#10#9#9#9#9'   AND  (y.DEPT_CODE, y.SRV_SITT' +
        'N_SNO) NOT IN (SELECT DEPT_CODE, SRV_SITTN_BFR_SNO'#10#9#9#9#9'         ' +
        '                                      FROM   TN_SRVSERWS002'#10#9#9#9#9 +
        '                                               WHERE  P_NO = x.P' +
        '_NO'#10#9#9#9#9'                                               AND    CH' +
        'G_YN = '#39'$'#39#10#9#9#9#9'                                               AN' +
        'D    y.CONFM_STTUS_CODE NOT IN ('#39'$'#39', '#39'$'#39'))'#10#9#9#9#9'order by sort_gb1' +
        ', y.begin_Ymd desc, sort_gb2 asc'#10#9#9#9#9'/* edusys.ga.srv.ser.ws.dbi' +
        'o.SrvSerWs00M00DQM.listSrvSittn.001 */'#10)
    ScrollBars = ssBoth
    TabOrder = 0
  end
  object Memo2: TMemo
    Left = 72
    Top = 288
    Width = 977
    Height = 57
    ImeName = 'Microsoft IME 2010'
    Lines.Strings = (
      
        '2,, ,SRV_SITTN_CODE,COP_CODE,1,4,.,5,2,.,7,2, ,1,2,:,3,2, ~ ,1,4' +
        ',.,5,2,.,7,2, ,1,2,:,3,2,0,1,0,0,Y,'#47588' ,,Y,'#47588' '
      
        ',,Y,:'#50668#48708#48512#51648#44553',,Y,'#49325#51228','#48120#49325#51228',4,Y,5,9,'#51076#49884#51200#51109',7,'#54924#49688',4,Y,'#50756#44208'('#44592#44208#52712#49548'),SANC_STTUS_C' +
        'ODE,SANC_STTUS_CODE,D, ,X,AAA,AAB,AAC,AAD,ABA,ABB,DAA,DAB,DAC,AA' +
        'B,1,2,Z,X,Z,10,10,6, '
      ',Y,4,5,%,%,%,1,1,4,5,Y,4,5,')
    TabOrder = 1
  end
  object Memo3: TMemo
    Left = 72
    Top = 352
    Width = 969
    Height = 73
    ImeName = 'Microsoft IME 2010'
    Lines.Strings = (
      
        #39#39','#39'M100000950'#39','#39'M100000950'#39','#39'M100000950'#39','#39'20110101'#39','#39'20111231'#39',' +
        #39'M100000950'#39','#39'20110101'#39','#39'20111231'#39','#39#39','#39#39','#39#39)
    TabOrder = 2
  end
  object Memo4: TMemo
    Left = 72
    Top = 448
    Width = 641
    Height = 177
    ImeName = 'Microsoft IME 2010'
    ScrollBars = ssBoth
    TabOrder = 3
  end
  object Button1: TButton
    Left = 840
    Top = 48
    Width = 75
    Height = 25
    Caption = 'Merge'
    TabOrder = 4
    OnClick = Button1Click
  end
  object Button2: TButton
    Left = 1000
    Top = 48
    Width = 75
    Height = 25
    Caption = 'Clear'
    TabOrder = 5
    OnClick = Button2Click
  end
  object Button3: TButton
    Left = 920
    Top = 48
    Width = 75
    Height = 25
    Caption = 'Copy'
    TabOrder = 6
    OnClick = Button3Click
  end
  object Memo5: TMemo
    Left = 1072
    Top = 184
    Width = 241
    Height = 401
    ImeName = 'Microsoft IME 2010'
    ScrollBars = ssBoth
    TabOrder = 7
  end
  object Edit1: TEdit
    Left = 1096
    Top = 104
    Width = 121
    Height = 21
    ImeName = 'Microsoft IME 2010'
    TabOrder = 8
    Text = 'Edit1'
  end
  object Edit2: TEdit
    Left = 1224
    Top = 104
    Width = 121
    Height = 21
    ImeName = 'Microsoft IME 2010'
    TabOrder = 9
    Text = 'Edit1'
  end
  object Edit3: TEdit
    Left = 1096
    Top = 144
    Width = 121
    Height = 21
    ImeName = 'Microsoft IME 2010'
    TabOrder = 10
    Text = 'Edit1'
  end
  object Edit4: TEdit
    Left = 1224
    Top = 144
    Width = 121
    Height = 21
    ImeName = 'Microsoft IME 2010'
    TabOrder = 11
    Text = 'Edit1'
  end
  object Edit5: TEdit
    Left = 1392
    Top = 152
    Width = 121
    Height = 21
    ImeName = 'Microsoft IME 2010'
    TabOrder = 12
    Text = 'Edit1'
  end
  object Memo6: TMemo
    Left = 720
    Top = 448
    Width = 161
    Height = 177
    ImeName = 'Microsoft IME 2010'
    ScrollBars = ssBoth
    TabOrder = 13
  end
  object Memo7: TMemo
    Left = 880
    Top = 448
    Width = 161
    Height = 177
    ImeName = 'Microsoft IME 2010'
    ScrollBars = ssBoth
    TabOrder = 14
  end
  object Memo8: TMemo
    Left = 1328
    Top = 184
    Width = 241
    Height = 401
    ImeName = 'Microsoft IME 2010'
    ScrollBars = ssBoth
    TabOrder = 15
  end
end
