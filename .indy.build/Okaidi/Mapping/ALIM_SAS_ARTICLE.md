<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.flow" id="_MGiYcNnUEe-ZLcaEU23iqA-flow" md:ref="resource.tech#_waYSMH8VEd2__Mzb_dB76A?fileId=_waYSMH8VEd2__Mzb_dB76A$type=tech$name=flow?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.flow.xdgHarvestRef" id="_AUvbwNqMEe-2vscanfRwMw" ref="resource.md#_MGiYcNnUEe-ZLcaEU23iqA-xdg?fileId=_MGiYcNnUEe-ZLcaEU23iqA-xdg$type=md?"/>
  <node defType="com.stambia.flow.altId" id="_AUlDsdqMEe-2vscanfRwMw">
    <attribute defType="com.stambia.flow.altId.origin" id="_AUlDstqMEe-2vscanfRwMw" value="mapping"/>
    <attribute defType="com.stambia.flow.altId.value" id="_AUlqwNqMEe-2vscanfRwMw" value="_MGiYcNnUEe-ZLcaEU23iqA"/>
  </node>
  <node defType="com.stambia.flow.step" id="08106d8e-7b4b-3d0d-ab9e-acbc26667b7f" name="I1_SAS_ARTICLE">
    <attribute defType="com.stambia.flow.step.number" id="_AUrKUdqMEe-2vscanfRwMw" value="1"/>
    <attribute defType="com.stambia.flow.step.target" id="_AUrKUtqMEe-2vscanfRwMw" value="$MD_0"/>
    <attribute defType="com.stambia.flow.step.type" id="_AUrKU9qMEe-2vscanfRwMw" value="Integration"/>
    <node defType="com.stambia.flow.source" id="_AUrKVNqMEe-2vscanfRwMw" name="L1_SAS_ARTICLE">
      <attribute defType="com.stambia.flow.source.stepName" id="_AUrKVdqMEe-2vscanfRwMw" value="L1_SAS_ARTICLE"/>
      <attribute defType="com.stambia.flow.source.number" id="_AUrKVtqMEe-2vscanfRwMw" value="1"/>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKV9qMEe-2vscanfRwMw" name="L1_COD_MRQ">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKWNqMEe-2vscanfRwMw" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKWdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKWtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKW9qMEe-2vscanfRwMw" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKXNqMEe-2vscanfRwMw" ref="resource.md#_kKMuONqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKXdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L1_COD_MRQ'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKXtqMEe-2vscanfRwMw" value="L1_COD_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKX9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKYNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKYdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKYtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L1_COD_MRQ</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKY9qMEe-2vscanfRwMw" name="L2_LIB_MRQ">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKZNqMEe-2vscanfRwMw" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKZdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKZtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKZ9qMEe-2vscanfRwMw" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKaNqMEe-2vscanfRwMw" ref="resource.md#_kKMuPtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKadqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L2_LIB_MRQ'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKatqMEe-2vscanfRwMw" value="L2_LIB_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKa9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKbNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKbdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKbtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L2_LIB_MRQ</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKb9qMEe-2vscanfRwMw" name="L3_COD_ART">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKcNqMEe-2vscanfRwMw" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKcdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKctqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKc9qMEe-2vscanfRwMw" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKdNqMEe-2vscanfRwMw" ref="resource.md#_kKMuRNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKddqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L3_COD_ART'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKdtqMEe-2vscanfRwMw" value="L3_COD_ART"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKd9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKeNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKedqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKetqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L3_COD_ART</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKe9qMEe-2vscanfRwMw" name="L4_LIB_PRD">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKfNqMEe-2vscanfRwMw" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKfdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKftqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKf9qMEe-2vscanfRwMw" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKgNqMEe-2vscanfRwMw" ref="resource.md#_kKMuStqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKgdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L4_LIB_PRD'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKgtqMEe-2vscanfRwMw" value="L4_LIB_PRD"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKg9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKhNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKhdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKhtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L4_LIB_PRD</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKh9qMEe-2vscanfRwMw" name="L5_LIB_COL">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKiNqMEe-2vscanfRwMw" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKidqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKitqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKi9qMEe-2vscanfRwMw" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKjNqMEe-2vscanfRwMw" ref="resource.md#_kKMuUNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKjdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L5_LIB_COL'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKjtqMEe-2vscanfRwMw" value="L5_LIB_COL"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKj9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKkNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKkdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKktqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L5_LIB_COL</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKk9qMEe-2vscanfRwMw" name="L6_LIB_TAI">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKlNqMEe-2vscanfRwMw" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKldqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKltqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKl9qMEe-2vscanfRwMw" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKmNqMEe-2vscanfRwMw" ref="resource.md#_kKMuVtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKmdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L6_LIB_TAI'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKmtqMEe-2vscanfRwMw" value="L6_LIB_TAI"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKm9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKnNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKndqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKntqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L6_LIB_TAI</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKn9qMEe-2vscanfRwMw" name="L7_FAM">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKoNqMEe-2vscanfRwMw" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKodqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKotqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKo9qMEe-2vscanfRwMw" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKpNqMEe-2vscanfRwMw" ref="resource.md#_kKMuXNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKpdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L7_FAM'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKptqMEe-2vscanfRwMw" value="L7_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKp9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKqNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKqdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKqtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L7_FAM</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKq9qMEe-2vscanfRwMw" name="L8_SS_FAM">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKrNqMEe-2vscanfRwMw" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKrdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKrtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKr9qMEe-2vscanfRwMw" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKsNqMEe-2vscanfRwMw" ref="resource.md#_kKMuYtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKsdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L8_SS_FAM'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKstqMEe-2vscanfRwMw" value="L8_SS_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKs9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKtNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKtdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKttqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L8_SS_FAM</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKt9qMEe-2vscanfRwMw" name="L9_PRX_VEN">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKuNqMEe-2vscanfRwMw" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKudqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKutqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKu9qMEe-2vscanfRwMw" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKvNqMEe-2vscanfRwMw" ref="resource.md#_kKNVIdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKvdqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L9_PRX_VEN'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKvtqMEe-2vscanfRwMw" value="L9_PRX_VEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKv9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKwNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKwdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKwtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L9_PRX_VEN</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKw9qMEe-2vscanfRwMw" name="L10_LIB_GEN">
      <attribute defType="com.stambia.flow.field.base" id="_AUrKxNqMEe-2vscanfRwMw" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrKxdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrKxtqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrKx9qMEe-2vscanfRwMw" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrKyNqMEe-2vscanfRwMw" ref="resource.md#_kKNVJ9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrKydqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L10_LIB_GEN'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrKytqMEe-2vscanfRwMw" value="L10_LIB_GEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrKy9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrKzNqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrKzdqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrKztqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L10_LIB_GEN</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrKz9qMEe-2vscanfRwMw" name="L11_CIB_TRN_AGE">
      <attribute defType="com.stambia.flow.field.base" id="_AUrK0NqMEe-2vscanfRwMw" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrK0dqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrK0tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrK09qMEe-2vscanfRwMw" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrK1NqMEe-2vscanfRwMw" ref="resource.md#_kKNVLdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrK1dqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L11_CIB_TRN_AGE'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrK1tqMEe-2vscanfRwMw" value="L11_CIB_TRN_AGE"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrK19qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrK2NqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrK2dqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrK2tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L11_CIB_TRN_AGE</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrK29qMEe-2vscanfRwMw" name="L12_COD_CAT">
      <attribute defType="com.stambia.flow.field.base" id="_AUrK3NqMEe-2vscanfRwMw" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrK3dqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrK3tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrK39qMEe-2vscanfRwMw" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrK4NqMEe-2vscanfRwMw" ref="resource.md#_kKNVM9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrK4dqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L12_COD_CAT'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrK4tqMEe-2vscanfRwMw" value="L12_COD_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrK49qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrK5NqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrK5dqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrK5tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L12_COD_CAT</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrK59qMEe-2vscanfRwMw" name="L13_LIB_CAT">
      <attribute defType="com.stambia.flow.field.base" id="_AUrK6NqMEe-2vscanfRwMw" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrK6dqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrK6tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrK69qMEe-2vscanfRwMw" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrK7NqMEe-2vscanfRwMw" ref="resource.md#_kKNVOdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrK7dqMEe-2vscanfRwMw" value="'L1_SAS_ARTICLE.L13_LIB_CAT'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrK7tqMEe-2vscanfRwMw" value="L13_LIB_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrK79qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_AUrK8NqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_AUrK8dqMEe-2vscanfRwMw" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrK8tqMEe-2vscanfRwMw">
        <values>L1_SAS_ARTICLE.L13_LIB_CAT</values>
      </attribute>
    </node>
  </node>
  <node defType="com.stambia.flow.step" id="0d98ff35-9598-33d5-a9b8-a5c7fcbe1092" name="L1_SAS_ARTICLE">
    <attribute defType="com.stambia.flow.step.number" id="_AUrxYdqMEe-2vscanfRwMw" value="1"/>
    <attribute defType="com.stambia.flow.step.integrationStepName" id="_AUrxYtqMEe-2vscanfRwMw">
      <values>I1_SAS_ARTICLE</values>
    </attribute>
    <attribute defType="com.stambia.flow.step.target" id="_AUrxY9qMEe-2vscanfRwMw" value="$MD_0"/>
    <attribute defType="com.stambia.flow.step.type" id="_AUrxZNqMEe-2vscanfRwMw" value="Load"/>
    <node defType="com.stambia.flow.source" id="_AUrxZdqMEe-2vscanfRwMw" name="Article">
      <attribute defType="com.stambia.flow.source.target" id="_AUrxZtqMEe-2vscanfRwMw" value="$MD_14"/>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxZ9qMEe-2vscanfRwMw" name="L1_COD_MRQ">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxaNqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxadqMEe-2vscanfRwMw" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxatqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxa9qMEe-2vscanfRwMw" value="1"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxbNqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxbdqMEe-2vscanfRwMw">
        <values>$MD_19</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxbtqMEe-2vscanfRwMw" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxb9qMEe-2vscanfRwMw" ref="resource.md#_kKMuONqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxcNqMEe-2vscanfRwMw" value="'Article.%{MD_19}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxcdqMEe-2vscanfRwMw" value="L1_COD_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxctqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxc9qMEe-2vscanfRwMw">
        <values>Article.%{MD_19}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxdNqMEe-2vscanfRwMw" name="L2_LIB_MRQ">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxddqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxdtqMEe-2vscanfRwMw" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxd9qMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxeNqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxedqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxetqMEe-2vscanfRwMw">
        <values>$MD_15</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxe9qMEe-2vscanfRwMw" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxfNqMEe-2vscanfRwMw" ref="resource.md#_kKMuPtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxfdqMEe-2vscanfRwMw" value="'Article.%{MD_15}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxftqMEe-2vscanfRwMw" value="L2_LIB_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxf9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxgNqMEe-2vscanfRwMw">
        <values>Article.%{MD_15}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxgdqMEe-2vscanfRwMw" name="L3_COD_ART">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxgtqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxg9qMEe-2vscanfRwMw" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxhNqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxhdqMEe-2vscanfRwMw" value="3"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxhtqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxh9qMEe-2vscanfRwMw">
        <values>$MD_17</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxiNqMEe-2vscanfRwMw" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxidqMEe-2vscanfRwMw" ref="resource.md#_kKMuRNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxitqMEe-2vscanfRwMw" value="'Article.%{MD_17}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxi9qMEe-2vscanfRwMw" value="L3_COD_ART"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxjNqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxjdqMEe-2vscanfRwMw">
        <values>Article.%{MD_17}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxjtqMEe-2vscanfRwMw" name="L4_LIB_PRD">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxj9qMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxkNqMEe-2vscanfRwMw" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxkdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxktqMEe-2vscanfRwMw" value="4"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxk9qMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxlNqMEe-2vscanfRwMw">
        <values>$MD_25</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxldqMEe-2vscanfRwMw" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxltqMEe-2vscanfRwMw" ref="resource.md#_kKMuStqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxl9qMEe-2vscanfRwMw" value="'Article.%{MD_25}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxmNqMEe-2vscanfRwMw" value="L4_LIB_PRD"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxmdqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxmtqMEe-2vscanfRwMw">
        <values>Article.%{MD_25}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxm9qMEe-2vscanfRwMw" name="L5_LIB_COL">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxnNqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxndqMEe-2vscanfRwMw" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxntqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxn9qMEe-2vscanfRwMw" value="5"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxoNqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxodqMEe-2vscanfRwMw">
        <values>$MD_26</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxotqMEe-2vscanfRwMw" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxo9qMEe-2vscanfRwMw" ref="resource.md#_kKMuUNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxpNqMEe-2vscanfRwMw" value="'Article.%{MD_26}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxpdqMEe-2vscanfRwMw" value="L5_LIB_COL"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxptqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxp9qMEe-2vscanfRwMw">
        <values>Article.%{MD_26}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxqNqMEe-2vscanfRwMw" name="L6_LIB_TAI">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxqdqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxqtqMEe-2vscanfRwMw" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxq9qMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxrNqMEe-2vscanfRwMw" value="6"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxrdqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxrtqMEe-2vscanfRwMw">
        <values>$MD_24</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxr9qMEe-2vscanfRwMw" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxsNqMEe-2vscanfRwMw" ref="resource.md#_kKMuVtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxsdqMEe-2vscanfRwMw" value="'Article.%{MD_24}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxstqMEe-2vscanfRwMw" value="L6_LIB_TAI"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxs9qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxtNqMEe-2vscanfRwMw">
        <values>Article.%{MD_24}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxtdqMEe-2vscanfRwMw" name="L7_FAM">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxttqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxt9qMEe-2vscanfRwMw" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxuNqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxudqMEe-2vscanfRwMw" value="7"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxutqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxu9qMEe-2vscanfRwMw">
        <values>$MD_22</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxvNqMEe-2vscanfRwMw" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxvdqMEe-2vscanfRwMw" ref="resource.md#_kKMuXNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxvtqMEe-2vscanfRwMw" value="'Article.%{MD_22}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxv9qMEe-2vscanfRwMw" value="L7_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxwNqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxwdqMEe-2vscanfRwMw">
        <values>Article.%{MD_22}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxwtqMEe-2vscanfRwMw" name="L8_SS_FAM">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrxw9qMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrxxNqMEe-2vscanfRwMw" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrxxdqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrxxtqMEe-2vscanfRwMw" value="8"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrxx9qMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrxyNqMEe-2vscanfRwMw">
        <values>$MD_20</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrxydqMEe-2vscanfRwMw" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrxytqMEe-2vscanfRwMw" ref="resource.md#_kKMuYtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrxy9qMEe-2vscanfRwMw" value="'Article.%{MD_20}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrxzNqMEe-2vscanfRwMw" value="L8_SS_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrxzdqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrxztqMEe-2vscanfRwMw">
        <values>Article.%{MD_20}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrxz9qMEe-2vscanfRwMw" name="L9_PRX_VEN">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrx0NqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrx0dqMEe-2vscanfRwMw" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrx0tqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrx09qMEe-2vscanfRwMw" value="9"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrx1NqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrx1dqMEe-2vscanfRwMw">
        <values>$MD_21</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrx1tqMEe-2vscanfRwMw" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrx19qMEe-2vscanfRwMw" ref="resource.md#_kKNVIdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrx2NqMEe-2vscanfRwMw" value="'Article.%{MD_21}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrx2dqMEe-2vscanfRwMw" value="L9_PRX_VEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrx2tqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrx29qMEe-2vscanfRwMw">
        <values>Article.%{MD_21}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrx3NqMEe-2vscanfRwMw" name="L10_LIB_GEN">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrx3dqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrx3tqMEe-2vscanfRwMw" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrx39qMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrx4NqMEe-2vscanfRwMw" value="10"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrx4dqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrx4tqMEe-2vscanfRwMw">
        <values>$MD_23</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrx49qMEe-2vscanfRwMw" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrx5NqMEe-2vscanfRwMw" ref="resource.md#_kKNVJ9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrx5dqMEe-2vscanfRwMw" value="'Article.%{MD_23}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrx5tqMEe-2vscanfRwMw" value="L10_LIB_GEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrx59qMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrx6NqMEe-2vscanfRwMw">
        <values>Article.%{MD_23}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrx6dqMEe-2vscanfRwMw" name="L11_CIB_TRN_AGE">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrx6tqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrx69qMEe-2vscanfRwMw" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrx7NqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrx7dqMEe-2vscanfRwMw" value="11"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrx7tqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrx79qMEe-2vscanfRwMw">
        <values>$MD_27</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrx8NqMEe-2vscanfRwMw" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrx8dqMEe-2vscanfRwMw" ref="resource.md#_kKNVLdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrx8tqMEe-2vscanfRwMw" value="'Article.%{MD_27}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUrx89qMEe-2vscanfRwMw" value="L11_CIB_TRN_AGE"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUrx9NqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUrx9dqMEe-2vscanfRwMw">
        <values>Article.%{MD_27}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUrx9tqMEe-2vscanfRwMw" name="L12_COD_CAT">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUrx99qMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUrx-NqMEe-2vscanfRwMw" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUrx-dqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUrx-tqMEe-2vscanfRwMw" value="12"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUrx-9qMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUrx_NqMEe-2vscanfRwMw">
        <values>$MD_16</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUrx_dqMEe-2vscanfRwMw" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUrx_tqMEe-2vscanfRwMw" ref="resource.md#_kKNVM9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUrx_9qMEe-2vscanfRwMw" value="'Article.%{MD_16}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUryANqMEe-2vscanfRwMw" value="L12_COD_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUryAdqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUryAtqMEe-2vscanfRwMw">
        <values>Article.%{MD_16}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_AUryA9qMEe-2vscanfRwMw" name="L13_LIB_CAT">
      <attribute defType="com.stambia.flow.field.aggregate" id="_AUryBNqMEe-2vscanfRwMw" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_AUryBdqMEe-2vscanfRwMw" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.location" id="_AUryBtqMEe-2vscanfRwMw" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_AUryB9qMEe-2vscanfRwMw" value="13"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_AUryCNqMEe-2vscanfRwMw">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_AUryCdqMEe-2vscanfRwMw">
        <values>$MD_18</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_AUryCtqMEe-2vscanfRwMw" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_AUryC9qMEe-2vscanfRwMw" ref="resource.md#_kKNVOdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_AUryDNqMEe-2vscanfRwMw" value="'Article.%{MD_18}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_AUryDdqMEe-2vscanfRwMw" value="L13_LIB_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_AUryDtqMEe-2vscanfRwMw" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_AUryD9qMEe-2vscanfRwMw">
        <values>Article.%{MD_18}%</values>
      </attribute>
    </node>
  </node>
  <metaDataLink name="MD_11" target="resource.md#_kKNVLdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
  <metaDataLink name="MD_18" target="resource.md#__Rgm3NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
  <metaDataLink name="MD_15" target="resource.md#__Rf_s9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
  <metaDataLink name="MD_22" target="resource.md#__RgmxNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=FAM?"/>
  <metaDataLink name="MD_14" target="resource.md#_U2H0MNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=Article?"/>
  <metaDataLink name="MD_16" target="resource.md#__Rgm2NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
  <metaDataLink name="MD_0" target="resource.md#_kKMuNdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SAS_ARTICLE?"/>
  <metaDataLink name="MD_8" target="resource.md#_kKMuYtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
  <metaDataLink name="MD_24" target="resource.md#__RgmwNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
  <metaDataLink name="MD_4" target="resource.md#_kKMuStqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
  <metaDataLink name="MD_3" target="resource.md#_kKMuRNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
  <metaDataLink name="MD_23" target="resource.md#__Rgm0NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
  <metaDataLink name="MD_7" target="resource.md#_kKMuXNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
  <metaDataLink name="MD_20" target="resource.md#__RgmyNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
  <metaDataLink name="MD_9" target="resource.md#_kKNVIdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
  <metaDataLink name="MD_5" target="resource.md#_kKMuUNqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
  <metaDataLink name="MD_6" target="resource.md#_kKMuVtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
  <metaDataLink name="MD_10" target="resource.md#_kKNVJ9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
  <metaDataLink name="MD_12" target="resource.md#_kKNVM9qKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
  <metaDataLink name="MD_19" target="resource.md#__RfYoNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
  <metaDataLink name="MD_25" target="resource.md#__Rf_u9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
  <metaDataLink name="MD_17" target="resource.md#__Rf_t9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
  <metaDataLink name="MD_2" target="resource.md#_kKMuPtqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
  <metaDataLink name="MD_26" target="resource.md#__Rf_v9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
  <metaDataLink name="MD_27" target="resource.md#__Rgm1NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
  <metaDataLink name="MD_1" target="resource.md#_kKMuONqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
  <metaDataLink name="MD_13" target="resource.md#_kKNVOdqKEe-2vscanfRwMw?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
  <metaDataLink name="MD_21" target="resource.md#__RgmzNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
</md:node>