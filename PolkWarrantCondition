<xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
  <xsl:strip-space elements="*"/>
  <xsl:output omit-xml-declaration="yes"/>
  <!--  *******************************************************************************************  * -->
<!--  *  Master Template for evaluating case event history to determine which CIP Pacakge          * -->
<!--  *  should fire.  Each CIP condition calls this template with the correct set of case events  * -->
<!--  *  Modification History.                                                                     * -->
<!--  *  2021-06-02 RED initial creation                                                           * -->
<!--  *******************************************************************************************  * -->
  <xsl:template name="Evaluate">
    
   <xsl:choose>
            <xsl:when test="/Integration/Warrant/@Op='A'">
                <xsl:if test="/Integration/Warrant[CaseCategory='CRN']">
				
                        true
						
                </xsl:if>
            </xsl:when>
        </xsl:choose>
	
	
	
  </xsl:template>
</xsl:stylesheet>
