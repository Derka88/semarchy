<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.flow" id="_Mtl70NtdEe-WqZzf9NOHeA-flow" md:ref="resource.tech#_waYSMH8VEd2__Mzb_dB76A?fileId=_waYSMH8VEd2__Mzb_dB76A$type=tech$name=flow?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.flow.xdgHarvestRef" id="_K_fgoNtwEe-WqZzf9NOHeA" ref="resource.md#_Mtl70NtdEe-WqZzf9NOHeA-xdg?fileId=_Mtl70NtdEe-WqZzf9NOHeA-xdg$type=md?"/>
  <node defType="com.stambia.flow.altId" id="_K_VIkdtwEe-WqZzf9NOHeA">
    <attribute defType="com.stambia.flow.altId.origin" id="_K_VIkttwEe-WqZzf9NOHeA" value="mapping"/>
    <attribute defType="com.stambia.flow.altId.value" id="_K_VIk9twEe-WqZzf9NOHeA" value="_Mtl70NtdEe-WqZzf9NOHeA"/>
  </node>
  <node defType="com.stambia.flow.step" id="e45d9e40-046d-32ef-94b7-9de75c31efdc" name="I1_SAS_PAYS">
    <attribute defType="com.stambia.flow.step.number" id="_K_bPMdtwEe-WqZzf9NOHeA" value="1"/>
    <attribute defType="com.stambia.flow.step.target" id="_K_bPMttwEe-WqZzf9NOHeA" value="$MD_0"/>
    <attribute defType="com.stambia.flow.step.type" id="_K_bPM9twEe-WqZzf9NOHeA" value="Integration"/>
    <node defType="com.stambia.flow.source" id="_K_bPNNtwEe-WqZzf9NOHeA" name="SAS_TICKET">
      <attribute defType="com.stambia.flow.source.target" id="_K_bPNdtwEe-WqZzf9NOHeA" value="$MD_3"/>
    </node>
    <node defType="com.stambia.flow.field" id="_K_bPNttwEe-WqZzf9NOHeA" name="COD_PAY">
      <attribute defType="com.stambia.flow.field.aggregate" id="_K_bPN9twEe-WqZzf9NOHeA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_K_bPONtwEe-WqZzf9NOHeA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.location" id="_K_bPOdtwEe-WqZzf9NOHeA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_K_bPOttwEe-WqZzf9NOHeA">
        <values>SAS_TICKET</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_K_bPO9twEe-WqZzf9NOHeA">
        <values>$MD_5</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_K_bPPNtwEe-WqZzf9NOHeA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_K_bPPdtwEe-WqZzf9NOHeA" ref="resource.md#_O6oo4NtiEe-WqZzf9NOHeA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_PAY?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_K_bPPttwEe-WqZzf9NOHeA" value="'SAS_TICKET.%{MD_5}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_K_bPP9twEe-WqZzf9NOHeA" value="COD_PAY"/>
      <attribute defType="com.stambia.flow.field.version" id="_K_bPQNtwEe-WqZzf9NOHeA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_K_bPQdtwEe-WqZzf9NOHeA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_K_bPQttwEe-WqZzf9NOHeA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_K_bPQ9twEe-WqZzf9NOHeA">
        <values>SAS_TICKET.%{MD_5}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_K_bPRNtwEe-WqZzf9NOHeA" name="LIB_PAY">
      <attribute defType="com.stambia.flow.field.aggregate" id="_K_bPRdtwEe-WqZzf9NOHeA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_K_bPRttwEe-WqZzf9NOHeA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.location" id="_K_bPR9twEe-WqZzf9NOHeA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_K_bPSNtwEe-WqZzf9NOHeA">
        <values>SAS_TICKET</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_K_bPSdtwEe-WqZzf9NOHeA">
        <values>$MD_4</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_K_bPSttwEe-WqZzf9NOHeA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_K_bPS9twEe-WqZzf9NOHeA" ref="resource.md#_O6oo5ttiEe-WqZzf9NOHeA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PAY?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_K_bPTNtwEe-WqZzf9NOHeA" value="'SAS_TICKET.%{MD_4}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_K_bPTdtwEe-WqZzf9NOHeA" value="LIB_PAY"/>
      <attribute defType="com.stambia.flow.field.version" id="_K_bPTttwEe-WqZzf9NOHeA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_K_bPT9twEe-WqZzf9NOHeA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_K_bPUNtwEe-WqZzf9NOHeA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_K_bPUdtwEe-WqZzf9NOHeA">
        <values>SAS_TICKET.%{MD_4}%</values>
      </attribute>
    </node>
  </node>
  <metaDataLink name="MD_2" target="resource.md#_O6oo5ttiEe-WqZzf9NOHeA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PAY?"/>
  <metaDataLink name="MD_4" target="resource.md#_QkiO_NqNEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PAY?"/>
  <metaDataLink name="MD_3" target="resource.md#_Qkhn9tqNEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SAS_TICKET?"/>
  <metaDataLink name="MD_5" target="resource.md#_QkiO9tqNEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_PAY?"/>
  <metaDataLink name="MD_0" target="resource.md#_O6oCPNtiEe-WqZzf9NOHeA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SAS_PAYS?"/>
  <metaDataLink name="MD_1" target="resource.md#_O6oo4NtiEe-WqZzf9NOHeA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_PAY?"/>
</md:node>