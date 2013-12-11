sugarcane
=========

'Sugarcane' is jaggery testing framework features (RC1)

1. Open <wso2 Product>\modules\p2-profile-gen\pom.xml 
2. Add below to <featureArtifacts>
`<featureArtifactDef>
sugarcane:sugarcane.feature:${sugarcane.feature.version}
</featureArtifactDef>`

5. Add below lines for <features>
`<feature>
<id>sugarcane .feature.group</id>
<version>${sugarcane.feature.version}</version>
</feature>`

6. Do  not forget to added sugarcane feature version in root pom <properties>
 `<sugarcane.feature.version>1.0.0-SNAPSHOT</sugarcane.feature.version>`

[More to read...](http://madhukaudantha.blogspot.com/2013/12/sugarcane-jaggery-test-framework-feature.html)
