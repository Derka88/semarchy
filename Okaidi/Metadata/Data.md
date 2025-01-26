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
    <node defType="com.stambia.rdbms.datastore" id="_kKMuNdqKEe-2vscanfRwMw" name="SAS_ARTICLE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kKMuNtqKEe-2vscanfRwMw" value="SAS_ARTICLE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kKMuN9qKEe-2vscanfRwMw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kKMuONqKEe-2vscanfRwMw" name="COD_MRQ" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuOdqKEe-2vscanfRwMw" value="COD_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuOtqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuO9qKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuPNqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuPdqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuPtqKEe-2vscanfRwMw" name="LIB_MRQ" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuP9qKEe-2vscanfRwMw" value="LIB_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuQNqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuQdqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuQtqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuQ9qKEe-2vscanfRwMw" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuRNqKEe-2vscanfRwMw" name="COD_ART" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuRdqKEe-2vscanfRwMw" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuRtqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuR9qKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuSNqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuSdqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuStqKEe-2vscanfRwMw" name="LIB_PRD" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuS9qKEe-2vscanfRwMw" value="LIB_PRD"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuTNqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuTdqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuTtqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuT9qKEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuUNqKEe-2vscanfRwMw" name="LIB_COL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuUdqKEe-2vscanfRwMw" value="LIB_COL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuUtqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuU9qKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuVNqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuVdqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuVtqKEe-2vscanfRwMw" name="LIB_TAI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuV9qKEe-2vscanfRwMw" value="LIB_TAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuWNqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuWdqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuWtqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuW9qKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuXNqKEe-2vscanfRwMw" name="FAM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuXdqKEe-2vscanfRwMw" value="FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuXtqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuX9qKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuYNqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKMuYdqKEe-2vscanfRwMw" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKMuYtqKEe-2vscanfRwMw" name="SS_FAM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKMuY9qKEe-2vscanfRwMw" value="SS_FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKMuZNqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKMuZdqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKMuZtqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVINqKEe-2vscanfRwMw" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKNVIdqKEe-2vscanfRwMw" name="PRX_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKNVItqKEe-2vscanfRwMw" value="PRX_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKNVI9qKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKNVJNqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKNVJdqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVJtqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKNVJ9qKEe-2vscanfRwMw" name="LIB_GEN" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKNVKNqKEe-2vscanfRwMw" value="LIB_GEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKNVKdqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKNVKtqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKNVK9qKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVLNqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKNVLdqKEe-2vscanfRwMw" name="CIB_TRN_AGE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKNVLtqKEe-2vscanfRwMw" value="CIB_TRN_AGE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKNVL9qKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKNVMNqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKNVMdqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVMtqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKNVM9qKEe-2vscanfRwMw" name="COD_CAT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKNVNNqKEe-2vscanfRwMw" value="COD_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKNVNdqKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKNVNtqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKNVN9qKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVONqKEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kKNVOdqKEe-2vscanfRwMw" name="LIB_CAT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_kKNVOtqKEe-2vscanfRwMw" value="LIB_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kKNVO9qKEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kKNVPNqKEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kKNVPdqKEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kKNVPtqKEe-2vscanfRwMw" value="100"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Qkhn9tqNEe-2vscanfRwMw" name="SAS_TICKET">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Qkhn99qNEe-2vscanfRwMw" value="SAS_TICKET"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Qkhn-NqNEe-2vscanfRwMw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Qkhn-dqNEe-2vscanfRwMw" name="COD_ENS" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qkhn-tqNEe-2vscanfRwMw" value="COD_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qkhn-9qNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qkhn_NqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qkhn_dqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qkhn_tqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qkhn_9qNEe-2vscanfRwMw" name="LIB_ENS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhoANqNEe-2vscanfRwMw" value="LIB_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkhoAdqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkhoAtqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkhoA9qNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkhoBNqNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkhoBdqNEe-2vscanfRwMw" name="LIB_MAG" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhoBtqNEe-2vscanfRwMw" value="LIB_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkhoB9qNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkhoCNqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkhoCdqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkhoCtqNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkhoC9qNEe-2vscanfRwMw" name="COD_ART" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhoDNqNEe-2vscanfRwMw" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkhoDdqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkhoDtqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkhoD9qNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkhoENqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkhoEdqNEe-2vscanfRwMw" name="DAT_HEU_TIC" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhoEtqNEe-2vscanfRwMw" value="DAT_HEU_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkhoE9qNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkhoFNqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkhoFdqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkhoFtqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkhoF9qNEe-2vscanfRwMw" name="NUM_TIC" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkhoGNqNEe-2vscanfRwMw" value="NUM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOsNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOsdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiOstqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiOs9qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiOtNqNEe-2vscanfRwMw" name="NUM_TIC_LIG" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiOtdqNEe-2vscanfRwMw" value="NUM_TIC_LIG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOttqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOt9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiOuNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiOudqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiOutqNEe-2vscanfRwMw" name="COD_CAI" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiOu9qNEe-2vscanfRwMw" value="COD_CAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOvNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOvdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiOvtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiOv9qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiOwNqNEe-2vscanfRwMw" name="COD_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiOwdqNEe-2vscanfRwMw" value="COD_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOwtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOw9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiOxNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiOxdqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiOxtqNEe-2vscanfRwMw" name="QTE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiOx9qNEe-2vscanfRwMw" value="QTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOyNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOydqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiOytqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiOy9qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiOzNqNEe-2vscanfRwMw" name="MNT_BRU" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiOzdqNEe-2vscanfRwMw" value="MNT_BRU"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiOztqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiOz9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO0NqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO0dqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO0tqNEe-2vscanfRwMw" name="MNT_TTC" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO09qNEe-2vscanfRwMw" value="MNT_TTC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO1NqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO1dqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO1tqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO19qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO2NqNEe-2vscanfRwMw" name="COD_DEV" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO2dqNEe-2vscanfRwMw" value="COD_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO2tqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO29qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO3NqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO3dqNEe-2vscanfRwMw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO3tqNEe-2vscanfRwMw" name="TX_TVA" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO39qNEe-2vscanfRwMw" value="TX_TVA"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO4NqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO4dqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO4tqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO49qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO5NqNEe-2vscanfRwMw" name="REM_LIN" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO5dqNEe-2vscanfRwMw" value="REM_LIN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO5tqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO59qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO6NqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO6dqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO6tqNEe-2vscanfRwMw" name="REM_TIC" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO69qNEe-2vscanfRwMw" value="REM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO7NqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO7dqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO7tqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO79qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO8NqNEe-2vscanfRwMw" name="TX_DEV" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO8dqNEe-2vscanfRwMw" value="TX_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO8tqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO89qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO9NqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO9dqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO9tqNEe-2vscanfRwMw" name="COD_PAY" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO99qNEe-2vscanfRwMw" value="COD_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO-NqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO-dqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiO-tqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiO-9qNEe-2vscanfRwMw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiO_NqNEe-2vscanfRwMw" name="LIB_PAY" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiO_dqNEe-2vscanfRwMw" value="LIB_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiO_tqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiO_9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPANqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPAdqNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPAtqNEe-2vscanfRwMw" name="ADR1" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPA9qNEe-2vscanfRwMw" value="ADR1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPBNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPBdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPBtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPB9qNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPCNqNEe-2vscanfRwMw" name="ADR2" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPCdqNEe-2vscanfRwMw" value="ADR2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPCtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPC9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPDNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPDdqNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPDtqNEe-2vscanfRwMw" name="ADR3" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPD9qNEe-2vscanfRwMw" value="ADR3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPENqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPEdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPEtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPE9qNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPFNqNEe-2vscanfRwMw" name="VIL_MAG" position="23">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPFdqNEe-2vscanfRwMw" value="VIL_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPFtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPF9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPGNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPGdqNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPGtqNEe-2vscanfRwMw" name="COD_POS" position="24">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPG9qNEe-2vscanfRwMw" value="COD_POS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPHNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPHdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPHtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPH9qNEe-2vscanfRwMw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPINqNEe-2vscanfRwMw" name="DEP_MAG" position="25">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPIdqNEe-2vscanfRwMw" value="DEP_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPItqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPI9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPJNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPJdqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPJtqNEe-2vscanfRwMw" name="REG_MAG" position="26">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPJ9qNEe-2vscanfRwMw" value="REG_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPKNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPKdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPKtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPK9qNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPLNqNEe-2vscanfRwMw" name="TEL" position="27">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPLdqNEe-2vscanfRwMw" value="TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPLtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPL9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPMNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPMdqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPMtqNEe-2vscanfRwMw" name="EMAIL" position="28">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPM9qNEe-2vscanfRwMw" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPNNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPNdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPNtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPN9qNEe-2vscanfRwMw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPONqNEe-2vscanfRwMw" name="LNG" position="29">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPOdqNEe-2vscanfRwMw" value="LNG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPOtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPO9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPPNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPPdqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPPtqNEe-2vscanfRwMw" name="LAT" position="30">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPP9qNEe-2vscanfRwMw" value="LAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPQNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPQdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPQtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPQ9qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPRNqNEe-2vscanfRwMw" name="DAT_OUV" position="31">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPRdqNEe-2vscanfRwMw" value="DAT_OUV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPRtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPR9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPSNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPSdqNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPStqNEe-2vscanfRwMw" name="DAT_FRM" position="32">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPS9qNEe-2vscanfRwMw" value="DAT_FRM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPTNqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPTdqNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPTtqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPT9qNEe-2vscanfRwMw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_QkiPUNqNEe-2vscanfRwMw" name="SCHEDULE" position="33">
        <attribute defType="com.stambia.rdbms.column.name" id="_QkiPUdqNEe-2vscanfRwMw" value="SCHEDULE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_QkiPUtqNEe-2vscanfRwMw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_QkiPU9qNEe-2vscanfRwMw" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_QkiPVNqNEe-2vscanfRwMw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_QkiPVdqNEe-2vscanfRwMw" value="250"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_O6oCPNtiEe-WqZzf9NOHeA" name="SAS_PAYS">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_O6oCPdtiEe-WqZzf9NOHeA" value="SAS_PAYS"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_O6oCPttiEe-WqZzf9NOHeA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_O6oo4NtiEe-WqZzf9NOHeA" name="COD_PAY" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_O6oo4dtiEe-WqZzf9NOHeA" value="COD_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_O6oo4ttiEe-WqZzf9NOHeA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_O6oo49tiEe-WqZzf9NOHeA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_O6oo5NtiEe-WqZzf9NOHeA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_O6oo5dtiEe-WqZzf9NOHeA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_O6oo5ttiEe-WqZzf9NOHeA" name="LIB_PAY" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_O6oo59tiEe-WqZzf9NOHeA" value="LIB_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_O6oo6NtiEe-WqZzf9NOHeA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_O6oo6dtiEe-WqZzf9NOHeA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_O6oo6ttiEe-WqZzf9NOHeA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_O6oo69tiEe-WqZzf9NOHeA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_YH8F8NtiEe-WqZzf9NOHeA" name="ID_PAYS" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_YH8F8dtiEe-WqZzf9NOHeA" value="ID_PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_YH8F8ttiEe-WqZzf9NOHeA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_YH8F89tiEe-WqZzf9NOHeA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_YH8F9NtiEe-WqZzf9NOHeA" value="NUMBER"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Un9hYNwNEe-ON53ZGnlopQ" name="SAS_REGION">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Un_WkNwNEe-ON53ZGnlopQ" value="SAS_REGION"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Un_9oNwNEe-ON53ZGnlopQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_VvB3INwNEe-ON53ZGnlopQ" name="ID_REG" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_VvB3IdwNEe-ON53ZGnlopQ" value="ID_REG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VvB3ItwNEe-ON53ZGnlopQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VvB3I9wNEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VvB3JNwNEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VvETYNwNEe-ON53ZGnlopQ" name="REG_MAG" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_VvETYdwNEe-ON53ZGnlopQ" value="REG_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VvETYtwNEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VvETY9wNEe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VvETZNwNEe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VvETZdwNEe-ON53ZGnlopQ" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_2JRU4NwNEe-ON53ZGnlopQ" name="ID_PAYS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_2JRU4dwNEe-ON53ZGnlopQ" value="ID_PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_2JRU4twNEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_2JRU49wNEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_2JRU5NwNEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_WDcn8NwNEe-ON53ZGnlopQ" name="SAS_DEP">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_WDdPANwNEe-ON53ZGnlopQ" value="SAS_DEP"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_WDdPAdwNEe-ON53ZGnlopQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_WIQPcNwNEe-ON53ZGnlopQ" name="ID_DEP" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_WIQPcdwNEe-ON53ZGnlopQ" value="ID_DEP"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_WIQPctwNEe-ON53ZGnlopQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_WIQPc9wNEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_WIQPdNwNEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_WISEoNwNEe-ON53ZGnlopQ" name="DEP_MAG" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_WISEodwNEe-ON53ZGnlopQ" value="DEP_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_WISEotwNEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_WISrsNwNEe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_WISrsdwNEe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_WISrstwNEe-ON53ZGnlopQ" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_3r4-MNwNEe-ON53ZGnlopQ" name="ID_REG" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_3r4-MdwNEe-ON53ZGnlopQ" value="ID_REG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_3r4-MtwNEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_3r4-M9wNEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_3r5lQNwNEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ZmGIEdwQEe-ON53ZGnlopQ" name="SAS_VILLE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ZmGIEtwQEe-ON53ZGnlopQ" value="SAS_VILLE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ZmGIE9wQEe-ON53ZGnlopQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ZmGIFNwQEe-ON53ZGnlopQ" name="ID_VILLE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ZmGIFdwQEe-ON53ZGnlopQ" value="ID_VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ZmGIFtwQEe-ON53ZGnlopQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ZmGIF9wQEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ZmGIGNwQEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ZmGIGdwQEe-ON53ZGnlopQ" name="VILLE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ZmGIGtwQEe-ON53ZGnlopQ" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ZmGIG9wQEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ZmGIHNwQEe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ZmGIHdwQEe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ZmGIHtwQEe-ON53ZGnlopQ" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ZmGIH9wQEe-ON53ZGnlopQ" name="COD_POS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ZmGIINwQEe-ON53ZGnlopQ" value="COD_POS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ZmGIIdwQEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ZmGIItwQEe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ZmGII9wQEe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ZmGIJNwQEe-ON53ZGnlopQ" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ZmGIJdwQEe-ON53ZGnlopQ" name="ID_DEP" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ZmGIJtwQEe-ON53ZGnlopQ" value="ID_DEP"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ZmGIJ9wQEe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ZmGIKNwQEe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ZmGIKdwQEe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_NNohjdwREe-ON53ZGnlopQ" name="SAS_MAGASIN">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_NNohjtwREe-ON53ZGnlopQ" value="SAS_MAGASIN"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_NNohj9wREe-ON53ZGnlopQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_NNohkNwREe-ON53ZGnlopQ" name="ID_MAG" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohkdwREe-ON53ZGnlopQ" value="ID_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohktwREe-ON53ZGnlopQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohk9wREe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohlNwREe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohldwREe-ON53ZGnlopQ" name="LIB_MAG" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohltwREe-ON53ZGnlopQ" value="LIB_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohl9wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohmNwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohmdwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohmtwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohm9wREe-ON53ZGnlopQ" name="COD_ENS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohnNwREe-ON53ZGnlopQ" value="COD_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohndwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohntwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohn9wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohoNwREe-ON53ZGnlopQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohodwREe-ON53ZGnlopQ" name="LIB_ENS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohotwREe-ON53ZGnlopQ" value="LIB_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNoho9wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohpNwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohpdwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohptwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohp9wREe-ON53ZGnlopQ" name="TEL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohqNwREe-ON53ZGnlopQ" value="TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohqdwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohqtwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohq9wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohrNwREe-ON53ZGnlopQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohrdwREe-ON53ZGnlopQ" name="EMAIL" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohrtwREe-ON53ZGnlopQ" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohr9wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohsNwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohsdwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohstwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohs9wREe-ON53ZGnlopQ" name="DAT_OUV" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohtNwREe-ON53ZGnlopQ" value="DAT_OUV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohtdwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohttwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNoht9wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohuNwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohudwREe-ON53ZGnlopQ" name="DAT_FRM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohutwREe-ON53ZGnlopQ" value="DAT_FRM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohu9wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohvNwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohvdwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohvtwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohv9wREe-ON53ZGnlopQ" name="SCHEDULE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohwNwREe-ON53ZGnlopQ" value="SCHEDULE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohwdwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohwtwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohw9wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohxNwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohxdwREe-ON53ZGnlopQ" name="ADR1" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohxtwREe-ON53ZGnlopQ" value="ADR1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohx9wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohyNwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohydwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNohytwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNohy9wREe-ON53ZGnlopQ" name="ADR2" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNohzNwREe-ON53ZGnlopQ" value="ADR2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNohzdwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNohztwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNohz9wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNoh0NwREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNoh0dwREe-ON53ZGnlopQ" name="ADR3" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNoh0twREe-ON53ZGnlopQ" value="ADR3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNoh09wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNoh1NwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNoh1dwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNoh1twREe-ON53ZGnlopQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNoh19wREe-ON53ZGnlopQ" name="LNG" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNoh2NwREe-ON53ZGnlopQ" value="LNG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNoh2dwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNoh2twREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNoh29wREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNoh3NwREe-ON53ZGnlopQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNoh3dwREe-ON53ZGnlopQ" name="LAT" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNoh3twREe-ON53ZGnlopQ" value="LAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNoh39wREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNoh4NwREe-ON53ZGnlopQ" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNoh4dwREe-ON53ZGnlopQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_NNoh4twREe-ON53ZGnlopQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_NNoh49wREe-ON53ZGnlopQ" name="ID_VILLE" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_NNoh5NwREe-ON53ZGnlopQ" value="ID_VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_NNpIENwREe-ON53ZGnlopQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_NNpIEdwREe-ON53ZGnlopQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_NNpIEtwREe-ON53ZGnlopQ" value="NUMBER"/>
      </node>
    </node>
  </node>
</md:node>