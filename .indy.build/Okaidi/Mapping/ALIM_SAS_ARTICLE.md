<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.flow" id="_MGiYcNnUEe-ZLcaEU23iqA-flow" md:ref="resource.tech#_waYSMH8VEd2__Mzb_dB76A?fileId=_waYSMH8VEd2__Mzb_dB76A$type=tech$name=flow?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.flow.xdgHarvestRef" id="_RBIDINnUEe-ZLcaEU23iqA" ref="resource.md#_MGiYcNnUEe-ZLcaEU23iqA-xdg?fileId=_MGiYcNnUEe-ZLcaEU23iqA-xdg$type=md?"/>
  <node defType="com.stambia.flow.altId" id="_RAz6EdnUEe-ZLcaEU23iqA">
    <attribute defType="com.stambia.flow.altId.origin" id="_RAz6EtnUEe-ZLcaEU23iqA" value="mapping"/>
    <attribute defType="com.stambia.flow.altId.value" id="_RAz6E9nUEe-ZLcaEU23iqA" value="_MGiYcNnUEe-ZLcaEU23iqA"/>
  </node>
  <node defType="com.stambia.flow.step" id="08106d8e-7b4b-3d0d-ab9e-acbc26667b7f" name="I1_SAS_ARTICLE">
    <attribute defType="com.stambia.flow.step.number" id="_RA-SIdnUEe-ZLcaEU23iqA" value="1"/>
    <attribute defType="com.stambia.flow.step.target" id="_RA-SItnUEe-ZLcaEU23iqA" value="$MD_0"/>
    <attribute defType="com.stambia.flow.step.type" id="_RA-SI9nUEe-ZLcaEU23iqA" value="Integration"/>
    <node defType="com.stambia.flow.source" id="_RA-SJNnUEe-ZLcaEU23iqA" name="L1_SAS_ARTICLE">
      <attribute defType="com.stambia.flow.source.stepName" id="_RA-SJdnUEe-ZLcaEU23iqA" value="L1_SAS_ARTICLE"/>
      <attribute defType="com.stambia.flow.source.number" id="_RA-SJtnUEe-ZLcaEU23iqA" value="1"/>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SJ9nUEe-ZLcaEU23iqA" name="L1_COD_MRQ">
      <attribute defType="com.stambia.flow.field.base" id="_RA-SKNnUEe-ZLcaEU23iqA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-SKdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SKtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-SK9nUEe-ZLcaEU23iqA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SLNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YPdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SLdnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L1_COD_MRQ'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SLtnUEe-ZLcaEU23iqA" value="L1_COD_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-SL9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SMNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SMdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SMtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L1_COD_MRQ</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SM9nUEe-ZLcaEU23iqA" name="L2_LIB_MRQ">
      <attribute defType="com.stambia.flow.field.base" id="_RA-SNNnUEe-ZLcaEU23iqA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-SNdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SNtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-SN9nUEe-ZLcaEU23iqA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SONnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YQ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SOdnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L2_LIB_MRQ'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SOtnUEe-ZLcaEU23iqA" value="L2_LIB_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-SO9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SPNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SPdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SPtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L2_LIB_MRQ</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SP9nUEe-ZLcaEU23iqA" name="L3_COD_ART">
      <attribute defType="com.stambia.flow.field.base" id="_RA-SQNnUEe-ZLcaEU23iqA" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-SQdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SQtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-SQ9nUEe-ZLcaEU23iqA" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SRNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YSdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SRdnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L3_COD_ART'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SRtnUEe-ZLcaEU23iqA" value="L3_COD_ART"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-SR9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SSNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SSdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SStnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L3_COD_ART</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SS9nUEe-ZLcaEU23iqA" name="L4_LIB_PRD">
      <attribute defType="com.stambia.flow.field.base" id="_RA-STNnUEe-ZLcaEU23iqA" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-STdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-STtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-ST9nUEe-ZLcaEU23iqA" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SUNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YT9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SUdnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L4_LIB_PRD'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SUtnUEe-ZLcaEU23iqA" value="L4_LIB_PRD"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-SU9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SVNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SVdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SVtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L4_LIB_PRD</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SV9nUEe-ZLcaEU23iqA" name="L5_LIB_COL">
      <attribute defType="com.stambia.flow.field.base" id="_RA-SWNnUEe-ZLcaEU23iqA" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-SWdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SWtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-SW9nUEe-ZLcaEU23iqA" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SXNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YVdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SXdnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L5_LIB_COL'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SXtnUEe-ZLcaEU23iqA" value="L5_LIB_COL"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-SX9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SYNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SYdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SYtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L5_LIB_COL</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-SY9nUEe-ZLcaEU23iqA" name="L6_LIB_TAI">
      <attribute defType="com.stambia.flow.field.base" id="_RA-SZNnUEe-ZLcaEU23iqA" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-SZdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SZtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-SZ9nUEe-ZLcaEU23iqA" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SaNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YW9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-SadnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L6_LIB_TAI'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-SatnUEe-ZLcaEU23iqA" value="L6_LIB_TAI"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-Sa9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-SbNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-SbdnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-SbtnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L6_LIB_TAI</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-Sb9nUEe-ZLcaEU23iqA" name="L7_FAM">
      <attribute defType="com.stambia.flow.field.base" id="_RA-ScNnUEe-ZLcaEU23iqA" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-ScdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-SctnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-Sc9nUEe-ZLcaEU23iqA" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-SdNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YYdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5MNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L7_FAM'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5MdnUEe-ZLcaEU23iqA" value="L7_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5MtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5M9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5NNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5NdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L7_FAM</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5NtnUEe-ZLcaEU23iqA" name="L8_SS_FAM">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5N9nUEe-ZLcaEU23iqA" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5ONnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5OdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5OtnUEe-ZLcaEU23iqA" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5O9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YZ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5PNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L8_SS_FAM'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5PdnUEe-ZLcaEU23iqA" value="L8_SS_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5PtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5P9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5QNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5QdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L8_SS_FAM</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5QtnUEe-ZLcaEU23iqA" name="L9_PRX_VEN">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5Q9nUEe-ZLcaEU23iqA" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5RNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5RdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5RtnUEe-ZLcaEU23iqA" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5R9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YbdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5SNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L9_PRX_VEN'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5SdnUEe-ZLcaEU23iqA" value="L9_PRX_VEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5StnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5S9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5TNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5TdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L9_PRX_VEN</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5TtnUEe-ZLcaEU23iqA" name="L10_LIB_GEN">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5T9nUEe-ZLcaEU23iqA" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5UNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5UdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5UtnUEe-ZLcaEU23iqA" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5U9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YdNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5VNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L10_LIB_GEN'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5VdnUEe-ZLcaEU23iqA" value="L10_LIB_GEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5VtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5V9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5WNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5WdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L10_LIB_GEN</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5WtnUEe-ZLcaEU23iqA" name="L11_CIB_TRN_AGE">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5W9nUEe-ZLcaEU23iqA" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5XNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5XdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5XtnUEe-ZLcaEU23iqA" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5X9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YetnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5YNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L11_CIB_TRN_AGE'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5YdnUEe-ZLcaEU23iqA" value="L11_CIB_TRN_AGE"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5YtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5Y9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5ZNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5ZdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L11_CIB_TRN_AGE</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5ZtnUEe-ZLcaEU23iqA" name="L12_COD_CAT">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5Z9nUEe-ZLcaEU23iqA" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5aNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5adnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5atnUEe-ZLcaEU23iqA" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5a9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YgNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5bNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L12_COD_CAT'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5bdnUEe-ZLcaEU23iqA" value="L12_COD_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5btnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5b9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5cNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5cdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L12_COD_CAT</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5ctnUEe-ZLcaEU23iqA" name="L13_LIB_CAT">
      <attribute defType="com.stambia.flow.field.base" id="_RA-5c9nUEe-ZLcaEU23iqA" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5dNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5ddnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5dtnUEe-ZLcaEU23iqA" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5d9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YhtnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5eNnUEe-ZLcaEU23iqA" value="'L1_SAS_ARTICLE.L13_LIB_CAT'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5ednUEe-ZLcaEU23iqA" value="L13_LIB_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5etnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.insert" id="_RA-5e9nUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.update" id="_RA-5fNnUEe-ZLcaEU23iqA" value="true"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5fdnUEe-ZLcaEU23iqA">
        <values>L1_SAS_ARTICLE.L13_LIB_CAT</values>
      </attribute>
    </node>
  </node>
  <node defType="com.stambia.flow.step" id="0d98ff35-9598-33d5-a9b8-a5c7fcbe1092" name="L1_SAS_ARTICLE">
    <attribute defType="com.stambia.flow.step.number" id="_RA-5f9nUEe-ZLcaEU23iqA" value="1"/>
    <attribute defType="com.stambia.flow.step.integrationStepName" id="_RA-5gNnUEe-ZLcaEU23iqA">
      <values>I1_SAS_ARTICLE</values>
    </attribute>
    <attribute defType="com.stambia.flow.step.target" id="_RA-5gdnUEe-ZLcaEU23iqA" value="$MD_0"/>
    <attribute defType="com.stambia.flow.step.type" id="_RA-5gtnUEe-ZLcaEU23iqA" value="Load"/>
    <node defType="com.stambia.flow.source" id="_RA-5g9nUEe-ZLcaEU23iqA" name="Article">
      <attribute defType="com.stambia.flow.source.target" id="_RA-5hNnUEe-ZLcaEU23iqA" value="$MD_14"/>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5hdnUEe-ZLcaEU23iqA" name="L1_COD_MRQ">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA-5htnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA-5h9nUEe-ZLcaEU23iqA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5iNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA-5idnUEe-ZLcaEU23iqA" value="1"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5itnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA-5i9nUEe-ZLcaEU23iqA">
        <values>$MD_20</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5jNnUEe-ZLcaEU23iqA" value="$MD_1"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5jdnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YPdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5jtnUEe-ZLcaEU23iqA" value="'Article.%{MD_20}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5j9nUEe-ZLcaEU23iqA" value="L1_COD_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5kNnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA-5kdnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_20}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA-5ktnUEe-ZLcaEU23iqA" name="L2_LIB_MRQ">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA-5k9nUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA-5lNnUEe-ZLcaEU23iqA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA-5ldnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA-5ltnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA-5l9nUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA-5mNnUEe-ZLcaEU23iqA">
        <values>$MD_25</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA-5mdnUEe-ZLcaEU23iqA" value="$MD_2"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA-5mtnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YQ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA-5m9nUEe-ZLcaEU23iqA" value="'Article.%{MD_25}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA-5nNnUEe-ZLcaEU23iqA" value="L2_LIB_MRQ"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA-5ndnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gQNnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_25}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gQdnUEe-ZLcaEU23iqA" name="L3_COD_ART">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gQtnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gQ9nUEe-ZLcaEU23iqA" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gRNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gRdnUEe-ZLcaEU23iqA" value="3"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gRtnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gR9nUEe-ZLcaEU23iqA">
        <values>$MD_19</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gSNnUEe-ZLcaEU23iqA" value="$MD_3"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gSdnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YSdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gStnUEe-ZLcaEU23iqA" value="'Article.%{MD_19}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gS9nUEe-ZLcaEU23iqA" value="L3_COD_ART"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gTNnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gTdnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_19}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gTtnUEe-ZLcaEU23iqA" name="L4_LIB_PRD">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gT9nUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gUNnUEe-ZLcaEU23iqA" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gUdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gUtnUEe-ZLcaEU23iqA" value="4"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gU9nUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gVNnUEe-ZLcaEU23iqA">
        <values>$MD_16</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gVdnUEe-ZLcaEU23iqA" value="$MD_4"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gVtnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YT9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gV9nUEe-ZLcaEU23iqA" value="'Article.%{MD_16}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gWNnUEe-ZLcaEU23iqA" value="L4_LIB_PRD"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gWdnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gWtnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_16}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gW9nUEe-ZLcaEU23iqA" name="L5_LIB_COL">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gXNnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gXdnUEe-ZLcaEU23iqA" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gXtnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gX9nUEe-ZLcaEU23iqA" value="5"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gYNnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gYdnUEe-ZLcaEU23iqA">
        <values>$MD_24</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gYtnUEe-ZLcaEU23iqA" value="$MD_5"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gY9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YVdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gZNnUEe-ZLcaEU23iqA" value="'Article.%{MD_24}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gZdnUEe-ZLcaEU23iqA" value="L5_LIB_COL"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gZtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gZ9nUEe-ZLcaEU23iqA">
        <values>Article.%{MD_24}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gaNnUEe-ZLcaEU23iqA" name="L6_LIB_TAI">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gadnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gatnUEe-ZLcaEU23iqA" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_ga9nUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gbNnUEe-ZLcaEU23iqA" value="6"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gbdnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gbtnUEe-ZLcaEU23iqA">
        <values>$MD_22</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gb9nUEe-ZLcaEU23iqA" value="$MD_6"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gcNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YW9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gcdnUEe-ZLcaEU23iqA" value="'Article.%{MD_22}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gctnUEe-ZLcaEU23iqA" value="L6_LIB_TAI"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gc9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gdNnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_22}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gddnUEe-ZLcaEU23iqA" name="L7_FAM">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gdtnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gd9nUEe-ZLcaEU23iqA" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_geNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gednUEe-ZLcaEU23iqA" value="7"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_getnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_ge9nUEe-ZLcaEU23iqA">
        <values>$MD_26</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gfNnUEe-ZLcaEU23iqA" value="$MD_7"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gfdnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YYdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gftnUEe-ZLcaEU23iqA" value="'Article.%{MD_26}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gf9nUEe-ZLcaEU23iqA" value="L7_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_ggNnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_ggdnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_26}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_ggtnUEe-ZLcaEU23iqA" name="L8_SS_FAM">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gg9nUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_ghNnUEe-ZLcaEU23iqA" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_ghdnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_ghtnUEe-ZLcaEU23iqA" value="8"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gh9nUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_giNnUEe-ZLcaEU23iqA">
        <values>$MD_23</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gidnUEe-ZLcaEU23iqA" value="$MD_8"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gitnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YZ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gi9nUEe-ZLcaEU23iqA" value="'Article.%{MD_23}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gjNnUEe-ZLcaEU23iqA" value="L8_SS_FAM"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gjdnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gjtnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_23}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gj9nUEe-ZLcaEU23iqA" name="L9_PRX_VEN">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gkNnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gkdnUEe-ZLcaEU23iqA" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gktnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gk9nUEe-ZLcaEU23iqA" value="9"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_glNnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gldnUEe-ZLcaEU23iqA">
        <values>$MD_21</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gltnUEe-ZLcaEU23iqA" value="$MD_9"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gl9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YbdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gmNnUEe-ZLcaEU23iqA" value="'Article.%{MD_21}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gmdnUEe-ZLcaEU23iqA" value="L9_PRX_VEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gmtnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gm9nUEe-ZLcaEU23iqA">
        <values>Article.%{MD_21}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gnNnUEe-ZLcaEU23iqA" name="L10_LIB_GEN">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gndnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gntnUEe-ZLcaEU23iqA" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gn9nUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_goNnUEe-ZLcaEU23iqA" value="10"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_godnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gotnUEe-ZLcaEU23iqA">
        <values>$MD_18</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_go9nUEe-ZLcaEU23iqA" value="$MD_10"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gpNnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YdNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gpdnUEe-ZLcaEU23iqA" value="'Article.%{MD_18}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gptnUEe-ZLcaEU23iqA" value="L10_LIB_GEN"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gp9nUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gqNnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_18}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gqdnUEe-ZLcaEU23iqA" name="L11_CIB_TRN_AGE">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gqtnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gq9nUEe-ZLcaEU23iqA" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_grNnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_grdnUEe-ZLcaEU23iqA" value="11"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_grtnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gr9nUEe-ZLcaEU23iqA">
        <values>$MD_15</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gsNnUEe-ZLcaEU23iqA" value="$MD_11"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gsdnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YetnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gstnUEe-ZLcaEU23iqA" value="'Article.%{MD_15}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gs9nUEe-ZLcaEU23iqA" value="L11_CIB_TRN_AGE"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gtNnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gtdnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_15}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gttnUEe-ZLcaEU23iqA" name="L12_COD_CAT">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gt9nUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_guNnUEe-ZLcaEU23iqA" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gudnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gutnUEe-ZLcaEU23iqA" value="12"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gu9nUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gvNnUEe-ZLcaEU23iqA">
        <values>$MD_27</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gvdnUEe-ZLcaEU23iqA" value="$MD_12"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gvtnUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YgNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gv9nUEe-ZLcaEU23iqA" value="'Article.%{MD_27}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gwNnUEe-ZLcaEU23iqA" value="L12_COD_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gwdnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gwtnUEe-ZLcaEU23iqA">
        <values>Article.%{MD_27}%</values>
      </attribute>
    </node>
    <node defType="com.stambia.flow.field" id="_RA_gw9nUEe-ZLcaEU23iqA" name="L13_LIB_CAT">
      <attribute defType="com.stambia.flow.field.aggregate" id="_RA_gxNnUEe-ZLcaEU23iqA" value="false"/>
      <attribute defType="com.stambia.flow.field.base" id="_RA_gxdnUEe-ZLcaEU23iqA" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.location" id="_RA_gxtnUEe-ZLcaEU23iqA" value="SRC"/>
      <attribute defType="com.stambia.flow.field.number" id="_RA_gx9nUEe-ZLcaEU23iqA" value="13"/>
      <attribute defType="com.stambia.flow.field.sourceContainer" id="_RA_gyNnUEe-ZLcaEU23iqA">
        <values>Article</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.source" id="_RA_gydnUEe-ZLcaEU23iqA">
        <values>$MD_17</values>
      </attribute>
      <attribute defType="com.stambia.flow.field.target" id="_RA_gytnUEe-ZLcaEU23iqA" value="$MD_13"/>
      <attribute defType="com.stambia.flow.field.mdFieldRef" id="_RA_gy9nUEe-ZLcaEU23iqA" ref="resource.md#_Gr8YhtnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
      <attribute defType="com.stambia.flow.field.expr" id="_RA_gzNnUEe-ZLcaEU23iqA" value="'Article.%{MD_17}%'"/>
      <attribute defType="com.stambia.flow.field.workname" id="_RA_gzdnUEe-ZLcaEU23iqA" value="L13_LIB_CAT"/>
      <attribute defType="com.stambia.flow.field.version" id="_RA_gztnUEe-ZLcaEU23iqA" value="2"/>
      <attribute defType="com.stambia.flow.field.sourceNames" id="_RA_gz9nUEe-ZLcaEU23iqA">
        <values>Article.%{MD_17}%</values>
      </attribute>
    </node>
  </node>
  <metaDataLink name="MD_18" target="resource.md#__Rgm0NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
  <metaDataLink name="MD_24" target="resource.md#__Rf_v9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
  <metaDataLink name="MD_4" target="resource.md#_Gr8YT9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
  <metaDataLink name="MD_23" target="resource.md#__RgmyNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
  <metaDataLink name="MD_8" target="resource.md#_Gr8YZ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SS_FAM?"/>
  <metaDataLink name="MD_13" target="resource.md#_Gr8YhtnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
  <metaDataLink name="MD_20" target="resource.md#__RfYoNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
  <metaDataLink name="MD_15" target="resource.md#__Rgm1NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
  <metaDataLink name="MD_21" target="resource.md#__RgmzNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
  <metaDataLink name="MD_25" target="resource.md#__Rf_s9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
  <metaDataLink name="MD_2" target="resource.md#_Gr8YQ9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_MRQ?"/>
  <metaDataLink name="MD_6" target="resource.md#_Gr8YW9nUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
  <metaDataLink name="MD_12" target="resource.md#_Gr8YgNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
  <metaDataLink name="MD_22" target="resource.md#__RgmwNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_TAI?"/>
  <metaDataLink name="MD_0" target="resource.md#_Gr8YOtnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=SAS_ARTICLE?"/>
  <metaDataLink name="MD_14" target="resource.md#_U2H0MNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=Article?"/>
  <metaDataLink name="MD_7" target="resource.md#_Gr8YYdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=FAM?"/>
  <metaDataLink name="MD_11" target="resource.md#_Gr8YetnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=CIB_TRN_AGE?"/>
  <metaDataLink name="MD_27" target="resource.md#__Rgm2NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_CAT?"/>
  <metaDataLink name="MD_9" target="resource.md#_Gr8YbdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=PRX_VEN?"/>
  <metaDataLink name="MD_10" target="resource.md#_Gr8YdNnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_GEN?"/>
  <metaDataLink name="MD_19" target="resource.md#__Rf_t9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
  <metaDataLink name="MD_26" target="resource.md#__RgmxNnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=FAM?"/>
  <metaDataLink name="MD_1" target="resource.md#_Gr8YPdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_MRQ?"/>
  <metaDataLink name="MD_5" target="resource.md#_Gr8YVdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=LIB_COL?"/>
  <metaDataLink name="MD_17" target="resource.md#__Rgm3NnTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_CAT?"/>
  <metaDataLink name="MD_3" target="resource.md#_Gr8YSdnUEe-ZLcaEU23iqA?fileId=_3fJz0NnKEe-OZtJVOz9TVA$type=md$name=COD_ART?"/>
  <metaDataLink name="MD_16" target="resource.md#__Rf_u9nTEe-ZLcaEU23iqA?fileId=_wERdANnSEe-OZtJVOz9TVA$type=md$name=LIB_PRD?"/>
</md:node>