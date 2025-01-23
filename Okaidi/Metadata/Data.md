<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_3fJz0NnKEe-OZtJVOz9TVA" name="Data" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_3ffyENnKEe-OZtJVOz9TVA" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_brGooNnLEe-OZtJVOz9TVA" value="CSG1_ORA4"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_brUrENnLEe-OZtJVOz9TVA" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_brVSINnLEe-OZtJVOz9TVA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_brV5MNnLEe-OZtJVOz9TVA" value="E887CA1CF8D875D88B286A9B0DB0D6F1"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_brV5MdnLEe-OZtJVOz9TVA" value="jdbc:oracle:thin:@195.83.93.26 :1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_3raHINnKEe-OZtJVOz9TVA" name="CSG1_ORA4">
    <attribute defType="com.stambia.rdbms.schema.name" id="_3wSnINnKEe-OZtJVOz9TVA" value="CSG1_ORA4"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_3wXfoNnKEe-OZtJVOz9TVA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_3wgCgNnKEe-OZtJVOz9TVA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_3wh3sNnKEe-OZtJVOz9TVA" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_bsV-wNnLEe-OZtJVOz9TVA" name="TEST">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_bsWl0NnLEe-OZtJVOz9TVA" value="TEST"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_bsXM4NnLEe-OZtJVOz9TVA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_b5RAcNnLEe-OZtJVOz9TVA" name="COLONNE1" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5RngNnLEe-OZtJVOz9TVA" value="COLONNE1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5RngdnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5RngtnLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5Rng9nLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5RnhNnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5TcsNnLEe-OZtJVOz9TVA" name="COLONNE2" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5TcsdnLEe-OZtJVOz9TVA" value="COLONNE2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5TcstnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5Tcs9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5TctNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5TctdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5Uq0NnLEe-OZtJVOz9TVA" name="COLONNE3" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5Uq0dnLEe-OZtJVOz9TVA" value="COLONNE3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5Uq0tnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5Uq09nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5VR4NnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5VR4dnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5WgANnLEe-OZtJVOz9TVA" name="COLONNE4" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5WgAdnLEe-OZtJVOz9TVA" value="COLONNE4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5WgAtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5WgA9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5WgBNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5WgBdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5YVMNnLEe-OZtJVOz9TVA" name="COLONNE5" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5YVMdnLEe-OZtJVOz9TVA" value="COLONNE5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5YVMtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5YVM9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5YVNNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5YVNdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5axcNnLEe-OZtJVOz9TVA" name="COLONNE6" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5axcdnLEe-OZtJVOz9TVA" value="COLONNE6"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5axctnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5axc9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5axdNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5axddnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5b_kNnLEe-OZtJVOz9TVA" name="COLONNE7" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5b_kdnLEe-OZtJVOz9TVA" value="COLONNE7"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5b_ktnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5b_k9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5b_lNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5b_ldnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5dNsNnLEe-OZtJVOz9TVA" name="COLONNE8" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5dNsdnLEe-OZtJVOz9TVA" value="COLONNE8"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5dNstnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5dNs9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5d0wNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5d0wdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5fC4NnLEe-OZtJVOz9TVA" name="COLONNE9" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5fC4dnLEe-OZtJVOz9TVA" value="COLONNE9"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5fC4tnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5fC49nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5fC5NnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5fC5dnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5gRANnLEe-OZtJVOz9TVA" name="COLONNE10" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5gRAdnLEe-OZtJVOz9TVA" value="COLONNE10"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5gRAtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5gRA9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5gRBNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5gRBdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5iGMNnLEe-OZtJVOz9TVA" name="COLONNE11" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5iGMdnLEe-OZtJVOz9TVA" value="COLONNE11"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5iGMtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5iGM9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5iGNNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5iGNdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5j7YNnLEe-OZtJVOz9TVA" name="COLONNE12" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5j7YdnLEe-OZtJVOz9TVA" value="COLONNE12"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5j7YtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5j7Y9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5j7ZNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5j7ZdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_b5lJgNnLEe-OZtJVOz9TVA" name="COLONNE13" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_b5lJgdnLEe-OZtJVOz9TVA" value="COLONNE13"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_b5lJgtnLEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_b5lJg9nLEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_b5lJhNnLEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_b5lJhdnLEe-OZtJVOz9TVA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_jczmUNnSEe-OZtJVOz9TVA" name="SAS_TICKET">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jczmUdnSEe-OZtJVOz9TVA" value="SAS_TICKET"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jczmUtnSEe-OZtJVOz9TVA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_jczmU9nSEe-OZtJVOz9TVA" name="COD_ENS" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmVNnSEe-OZtJVOz9TVA" value="COD_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmVdnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmVtnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmV9nSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmWNnSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmWdnSEe-OZtJVOz9TVA" name="LIB_ENS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmWtnSEe-OZtJVOz9TVA" value="LIB_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmW9nSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmXNnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmXdnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmXtnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmX9nSEe-OZtJVOz9TVA" name="LIB_MAG" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmYNnSEe-OZtJVOz9TVA" value="LIB_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmYdnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmYtnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmY9nSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmZNnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmZdnSEe-OZtJVOz9TVA" name="COD_ART" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmZtnSEe-OZtJVOz9TVA" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmZ9nSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmaNnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmadnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmatnSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczma9nSEe-OZtJVOz9TVA" name="DAT_HEU_TIC" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmbNnSEe-OZtJVOz9TVA" value="DAT_HEU_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmbdnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmbtnSEe-OZtJVOz9TVA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmb9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmcNnSEe-OZtJVOz9TVA" value="TIMESTAMP(6)"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmcdnSEe-OZtJVOz9TVA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmctnSEe-OZtJVOz9TVA" name="NUM_TIC" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmc9nSEe-OZtJVOz9TVA" value="NUM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmdNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmddnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmdtnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmd9nSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmeNnSEe-OZtJVOz9TVA" name="NUM_TIC_LIG" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmednSEe-OZtJVOz9TVA" value="NUM_TIC_LIG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmetnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczme9nSEe-OZtJVOz9TVA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmfNnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmfdnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmftnSEe-OZtJVOz9TVA" value="22"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmf9nSEe-OZtJVOz9TVA" name="COD_CAI" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmgNnSEe-OZtJVOz9TVA" value="COD_CAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmgdnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmgtnSEe-OZtJVOz9TVA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmg9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmhNnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmhdnSEe-OZtJVOz9TVA" value="22"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmhtnSEe-OZtJVOz9TVA" name="COD_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmh9nSEe-OZtJVOz9TVA" value="COD_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmiNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmidnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmitnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmi9nSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmjNnSEe-OZtJVOz9TVA" name="QTE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmjdnSEe-OZtJVOz9TVA" value="QTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmjtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmj9nSEe-OZtJVOz9TVA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmkNnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmkdnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmktnSEe-OZtJVOz9TVA" value="22"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmk9nSEe-OZtJVOz9TVA" name="MNT_BRU" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmlNnSEe-OZtJVOz9TVA" value="MNT_BRU"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmldnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmltnSEe-OZtJVOz9TVA" value="5"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczml9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmmNnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmmdnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmmtnSEe-OZtJVOz9TVA" name="MNT_TTC" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmm9nSEe-OZtJVOz9TVA" value="MNT_TTC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmnNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmndnSEe-OZtJVOz9TVA" value="5"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmntnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmn9nSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmoNnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmodnSEe-OZtJVOz9TVA" name="COD_DEV" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmotnSEe-OZtJVOz9TVA" value="COD_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmo9nSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmpNnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmpdnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmptnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmp9nSEe-OZtJVOz9TVA" name="TX_TVA" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmqNnSEe-OZtJVOz9TVA" value="TX_TVA"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmqdnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmqtnSEe-OZtJVOz9TVA" value="2"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmq9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmrNnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmrdnSEe-OZtJVOz9TVA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmrtnSEe-OZtJVOz9TVA" name="REM_LIN" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmr9nSEe-OZtJVOz9TVA" value="REM_LIN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmsNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmsdnSEe-OZtJVOz9TVA" value="5"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmstnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczms9nSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmtNnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmtdnSEe-OZtJVOz9TVA" name="REM_TIC" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmttnSEe-OZtJVOz9TVA" value="REM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmt9nSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmuNnSEe-OZtJVOz9TVA" value="5"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmudnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmutnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmu9nSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jczmvNnSEe-OZtJVOz9TVA" name="TX_DEV" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_jczmvdnSEe-OZtJVOz9TVA" value="TX_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jczmvtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jczmv9nSEe-OZtJVOz9TVA" value="5"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jczmwNnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jczmwdnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jczmwtnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NQNnSEe-OZtJVOz9TVA" name="COD_PAY" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NQdnSEe-OZtJVOz9TVA" value="COD_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NQtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NQ9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NRNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NRdnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NRtnSEe-OZtJVOz9TVA" name="LIB_PAY" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NR9nSEe-OZtJVOz9TVA" value="LIB_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NSNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NSdnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NStnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NS9nSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NTNnSEe-OZtJVOz9TVA" name="ADR1" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NTdnSEe-OZtJVOz9TVA" value="ADR1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NTtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NT9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NUNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NUdnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NUtnSEe-OZtJVOz9TVA" name="ADR2" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NU9nSEe-OZtJVOz9TVA" value="ADR2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NVNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NVdnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NVtnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NV9nSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NWNnSEe-OZtJVOz9TVA" name="ADR3" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NWdnSEe-OZtJVOz9TVA" value="ADR3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NWtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NW9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NXNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NXdnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NXtnSEe-OZtJVOz9TVA" name="VIL_MAG" position="23">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NX9nSEe-OZtJVOz9TVA" value="VIL_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NYNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NYdnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NYtnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NY9nSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NZNnSEe-OZtJVOz9TVA" name="COD_POS" position="24">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NZdnSEe-OZtJVOz9TVA" value="COD_POS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NZtnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NZ9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NaNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NadnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NatnSEe-OZtJVOz9TVA" name="DEP_MAG" position="25">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0Na9nSEe-OZtJVOz9TVA" value="DEP_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NbNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NbdnSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NbtnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0Nb9nSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NcNnSEe-OZtJVOz9TVA" name="REG_MAG" position="26">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NcdnSEe-OZtJVOz9TVA" value="REG_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NctnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0Nc9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NdNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NddnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NdtnSEe-OZtJVOz9TVA" name="TEL" position="27">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0Nd9nSEe-OZtJVOz9TVA" value="TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NeNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NednSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NetnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0Ne9nSEe-OZtJVOz9TVA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NfNnSEe-OZtJVOz9TVA" name="EMAIL" position="28">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NfdnSEe-OZtJVOz9TVA" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NftnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0Nf9nSEe-OZtJVOz9TVA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NgNnSEe-OZtJVOz9TVA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NgdnSEe-OZtJVOz9TVA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NgtnSEe-OZtJVOz9TVA" name="LNG" position="29">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0Ng9nSEe-OZtJVOz9TVA" value="LNG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NhNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jc0NhdnSEe-OZtJVOz9TVA" value="7"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NhtnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0Nh9nSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NiNnSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NidnSEe-OZtJVOz9TVA" name="LAT" position="30">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NitnSEe-OZtJVOz9TVA" value="LAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0Ni9nSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_jc0NjNnSEe-OZtJVOz9TVA" value="7"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NjdnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NjtnSEe-OZtJVOz9TVA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0Nj9nSEe-OZtJVOz9TVA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NkNnSEe-OZtJVOz9TVA" name="DAT_OUV" position="31">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NkdnSEe-OZtJVOz9TVA" value="DAT_OUV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NktnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0Nk9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NlNnSEe-OZtJVOz9TVA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NldnSEe-OZtJVOz9TVA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NltnSEe-OZtJVOz9TVA" name="DAT_FRM" position="32">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0Nl9nSEe-OZtJVOz9TVA" value="DAT_FRM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NmNnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0NmdnSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NmtnSEe-OZtJVOz9TVA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0Nm9nSEe-OZtJVOz9TVA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jc0NnNnSEe-OZtJVOz9TVA" name="SCHEDULE" position="33">
        <attribute defType="com.stambia.rdbms.column.name" id="_jc0NndnSEe-OZtJVOz9TVA" value="SCHEDULE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jc0NntnSEe-OZtJVOz9TVA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jc0Nn9nSEe-OZtJVOz9TVA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jc0NoNnSEe-OZtJVOz9TVA" value="CLOB"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jc0NodnSEe-OZtJVOz9TVA" value="4000"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Gr8YOtnUEe-ZLcaEU23iqA" name="SAS_ARTICLE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Gr8YO9nUEe-ZLcaEU23iqA" value="SAS_ARTICLE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Gr8YPNnUEe-ZLcaEU23iqA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Gr8YPdnUEe-ZLcaEU23iqA" name="COD_MRQ" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YPtnUEe-ZLcaEU23iqA" value="COD_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YP9nUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YQNnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YQdnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YQtnUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YQ9nUEe-ZLcaEU23iqA" name="LIB_MRQ" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YRNnUEe-ZLcaEU23iqA" value="LIB_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YRdnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YRtnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YR9nUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YSNnUEe-ZLcaEU23iqA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YSdnUEe-ZLcaEU23iqA" name="COD_ART" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YStnUEe-ZLcaEU23iqA" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YS9nUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YTNnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YTdnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YTtnUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YT9nUEe-ZLcaEU23iqA" name="LIB_PRD" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YUNnUEe-ZLcaEU23iqA" value="LIB_PRD"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YUdnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YUtnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YU9nUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YVNnUEe-ZLcaEU23iqA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YVdnUEe-ZLcaEU23iqA" name="LIB_COL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YVtnUEe-ZLcaEU23iqA" value="LIB_COL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YV9nUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YWNnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YWdnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YWtnUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YW9nUEe-ZLcaEU23iqA" name="LIB_TAI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YXNnUEe-ZLcaEU23iqA" value="LIB_TAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YXdnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YXtnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YX9nUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YYNnUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YYdnUEe-ZLcaEU23iqA" name="FAM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YYtnUEe-ZLcaEU23iqA" value="FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YY9nUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YZNnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YZdnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YZtnUEe-ZLcaEU23iqA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YZ9nUEe-ZLcaEU23iqA" name="SS_FAM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YaNnUEe-ZLcaEU23iqA" value="SS_FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YadnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YatnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8Ya9nUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YbNnUEe-ZLcaEU23iqA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YbdnUEe-ZLcaEU23iqA" name="PRX_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YbtnUEe-ZLcaEU23iqA" value="PRX_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8Yb9nUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Gr8YcNnUEe-ZLcaEU23iqA" value="2"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YcdnUEe-ZLcaEU23iqA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YctnUEe-ZLcaEU23iqA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8Yc9nUEe-ZLcaEU23iqA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YdNnUEe-ZLcaEU23iqA" name="LIB_GEN" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YddnUEe-ZLcaEU23iqA" value="LIB_GEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YdtnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8Yd9nUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YeNnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YednUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YetnUEe-ZLcaEU23iqA" name="CIB_TRN_AGE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8Ye9nUEe-ZLcaEU23iqA" value="CIB_TRN_AGE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YfNnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YfdnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YftnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8Yf9nUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YgNnUEe-ZLcaEU23iqA" name="COD_CAT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8YgdnUEe-ZLcaEU23iqA" value="COD_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YgtnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8Yg9nUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YhNnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8YhdnUEe-ZLcaEU23iqA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Gr8YhtnUEe-ZLcaEU23iqA" name="LIB_CAT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_Gr8Yh9nUEe-ZLcaEU23iqA" value="LIB_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Gr8YiNnUEe-ZLcaEU23iqA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Gr8YidnUEe-ZLcaEU23iqA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Gr8YitnUEe-ZLcaEU23iqA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Gr8Yi9nUEe-ZLcaEU23iqA" value="100"/>
      </node>
    </node>
  </node>
</md:node>