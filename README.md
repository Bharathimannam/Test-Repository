<?xml version='1.0' encoding='UTF-8'?>
<!DOCTYPE Application PUBLIC "sailpoint.dtd" "sailpoint.dtd">
<Application connector="sailpoint.connector.ADLDAPConnector" created="" featuresString="PROVISIONING, SYNC_PROVISIONING, AUTHENTICATE, MANAGER_LOOKUP, SEARCH, UNSTRUCTURED_TARGETS, UNLOCK, ENABLE, PASSWORD, CURRENT_PASSWORD, ADDITIONAL_ACCOUNT_REQUEST, ACCOUNT_ONLY_REQUEST" icon="directory1Icon" 
="" modified="" name="ActiveDirectoryApplication1" profileClass="" type="Active Directory - Direct">
  <AccountCorrelationConfig>
    <Reference class="sailpoint.object.CorrelationConfig" id="" name="targetCorrelation"/>
  </AccountCorrelationConfig>
  <Attributes>
    <Map>
      <entry key="ADAppVersion" value="V2"/>
      <entry key="IQServiceConfiguration">
        <value>
          <List>
            <Map>
              <entry key="IQServiceHost" value="192.168.222.128"/>
              <entry key="IQServicePassword" value="1:ACP:27Slt3Sbut2u3DbASGdDyLzST4q6DmzKvVcfUngu9lQ="/>
              <entry key="IQServicePort" value="5050"/>
              <entry key="IQServiceUser" value="Eshiam\Administrator"/>
              <entry key="useTLSForIQService">
                <value>
                  <Boolean></Boolean>
                </value>
              </entry>
            </Map>
          </List>
        </value>
      </entry>
      <entry key="Mode" value="Development"/>
      <entry key="acctAggregationEnd">
        <value>
          <Date>1717499573514</Date>
        </value>
      </entry>
      <entry key="acctAggregationStart">
        <value>
          <Date>1717499571381</Date>
        </value>
      </entry>
      <entry key="afterProvisioningRule"/>
      <entry key="allowAutoPartitioning">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="authSearchAttributes">
        <value>
          <List>
            <String>sAMAccountName</String>
            <String>msDS-PrincipalName</String>
            <String>mail</String>
          </List>
        </value>
      </entry>
      <entry key="autoPartitionCount" value="256"/>
      <entry key="beforeProvisioningRule" value="AD_Before Provisioning reule"/>
      <entry key="cacheRemoteObjectPort" value="40002"/>
      <entry key="cacheRmiPort" value="40001"/>
      <entry key="compositeDefinition"/>
      <entry key="deletedObjectsContainer" value="CN=Deleted Objects,DOMAIN"/>
      <entry key="deltaAggregation">
        <value>
          <Map>
            <entry key="dc=eshiam,dc=com">
              <value>
                <Map>
                  <entry key="groups_cookie" value="TVNEUwMAAABw2eY9cLbaAQAAAAAAAAAAQAAAAGfgAAAAAAAAAAAAAAAAAABn4AAAAAAAAIJX5mRf&#xD;&#xA;/8lKpcnkYUaibKUBAAAAAAAAAAIAAAAAAAAADARUXsHh6U6EWIFiZnKTMAmwAAAAAAAAglfmZF//&#xD;&#xA;yUqlyeRhRqJspWrgAAAAAAAA"/>
                  <entry key="lastDirsyncServer" value="192.168.222.128"/>
                  <entry key="users_cookie" value="TVNEUwMAAAB3a5wjcLbaAQAAAAAAAAAAQAAAAGfgAAAAAAAAAAAAAAAAAABn4AAAAAAAAIJX5mRf&#xD;&#xA;/8lKpcnkYUaibKUBAAAAAAAAAAIAAAAAAAAADARUXsHh6U6EWIFiZnKTMAmwAAAAAAAAglfmZF//&#xD;&#xA;yUqlyeRhRqJspWrgAAAAAAAA"/>
                </Map>
              </value>
            </entry>
          </Map>
        </value>
      </entry>
      <entry key="deltaIterationMode" value="dirSync"/>
      <entry key="disableComputePreloading">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="disableFspAggregation">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="displayAttributeForContacts" value="cn"/>
      <entry key="domainSettings">
        <value>
          <List>
            <Map>
              <entry key="authenticationType" value="simple"/>
              <entry key="authorizationType" value="simple"/>
              <entry key="domainDN" value="DC=Eshiam,DC=com"/>
              <entry key="domainIterateSearchFilter"/>
              <entry key="domainNetBiosName"/>
              <entry key="forestName" value="eshiam"/>
              <entry key="password" value="1:ACP:6n4wXdQe6UoZC8Inr+9+8HI55e0D7HN0CTzqJZxWQkY="/>
              <entry key="port" value="389"/>
              <entry key="servers">
                <value>
                  <List>
                    <String>192.168.222.128</String>
                  </List>
                </value>
              </entry>
              <entry key="useSSL">
                <value>
                  <Boolean></Boolean>
                </value>
              </entry>
              <entry key="user" value="Eshiam\Administrator"/>
            </Map>
          </List>
        </value>
      </entry>
      <entry key="enableCache">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="encrypted" value="domainSettings.password,forestSettings.password,exchangeSettings.password,IQServiceConfiguration.IQServicePassword"/>
      <entry key="forestSettings">
        <value>
          <List>
            <Map>
              <entry key="authenticationType" value="simple"/>
              <entry key="authorizationType" value="simple"/>
              <entry key="forestName" value="eshiam"/>
              <entry key="gcServer" value="192.168.222.128:3268"/>
              <entry key="isResourceForest">
                <value>
                  <Boolean></Boolean>
                </value>
              </entry>
              <entry key="manageAllDomains">
                <value>
                  <Boolean></Boolean>
                </value>
              </entry>
              <entry key="password" value="1:ACP:LvIQ3vIwhagp/d2UTre0mCUk9jIk1DOqI98ei/UzGRI="/>
              <entry key="useGroupMembershipPreloading"/>
              <entry key="useSSL">
                <value>
                  <Boolean></Boolean>
                </value>
              </entry>
              <entry key="user" value="Eshiam\Administrator"/>
            </Map>
          </List>
        </value>
      </entry>
      <entry key="group.searchDNs">
        <value>
          <List>
            <Map>
              <entry key="iterateSearchFilter"/>
              <entry key="searchDN" value="OU=Groups,OU=Demo,DC=Eshiam,DC=com"/>
              <entry key="searchScope" value="SUBTREE"/>
            </Map>
          </List>
        </value>
      </entry>
      <entry key="groupProvisioning">
        <value>
          <Boolean>true</Boolean>
        </value>
      </entry>
      <entry key="ldapExtendedControls">
        <value>
          <List>
            <String>1.2.840.113556.1.4.1339</String>
          </List>
        </value>
      </entry>
      <entry key="lyncAttributes" value="RegistrarPool,SipAddressType,SipAddress,SipDomain,msRTCSIP-UserEnabled"/>
      <entry key="manageLync">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="manageRecycleBin">
        <value>
          <Boolean></Boolean>
        </value>
      </entry>
      <entry key="nativeChangeDetectionAttributeScope" value="userDefined"/>
      <entry key="nativeChangeDetectionAttributes">
        <value>
          <List>
            <String>givenName</String>
            <String>sn</String>
            <String>memberOf</String>
            <String>mail</String>
            <String>manager</String>
          </List>
        </value>
      </entry>
      <entry key="nativeChangeDetectionEnabled">
        <value>
          <Boolean>true</Boolean>
        </value>
      </entry>
      <entry key="nativeChangeDetectionOperations">
        <value>
          <List>
            <String>Create</String>
            <String>Modify</String>
            <String>Delete</String>
          </List>
        </value>
      </entry>
      <entry key="noGroupPermissions">
        <value>
          <Map>
            <entry key="group">
              <value>
                <Boolean></Boolean>
              </value>
            </entry>
          </Map>
        </value>
      </entry>
      <entry key="noPermissions" value="false"/>
      <entry key="operations" value="Create, Modify, Delete, Enable, Disable, Unlock, SetPassword"/>
      <entry key="pageSize" value="100"/>
      <entry key="schemaProvisioningMap">
        <value>
          <Map>
            <entry key="group">
              <value>
                <Boolean>true</Boolean>
              </value>
            </entry>
          </Map>
        </value>
      </entry>
      <entry key="searchDNs">
        <value>
          <List>
            <Map>
              <entry key="groupMemberFilterString"/>
              <entry key="groupMembershipSearchDN"/>
              <entry key="iterateSearchFilter"/>
              <entry key="primaryGroupSearchDN"/>
              <entry key="searchDN" value="OU=Demo,DC=Eshiam,DC=com"/>
              <entry key="searchScope" value="SUBTREE"/>
            </Map>
          </List>
        </value>
      </entry>
      <entry key="sysDescriptions">
        <value>
          <Map>
            <entry key="en_US"/>
          </Map>
        </value>
      </entry>
      <entry key="templateApplication" value="Active Directory Template"/>
      <entry key="useSSL" value="false"/>
    </Map>
  </Attributes>
  <Owner>
    <Reference class="sailpoint.object.Identity" id="c0a800c78cec1fa8818cf1f30fe406a9" name="Amy Cox"/>
  </Owner>
  <ProvisioningForms>
    <Form name="Account" objectType="account" type="Create">
      <Attributes>
        <Map>
          <entry key="pageTitle" value="Account"/>
        </Map>
      </Attributes>
      <Section label="Account" name="Account">
        <Field displayName="hello" name="objectType" postBack="true" section="Account" type="string" value="User">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>User</String>
                <String>Contact</String>
                <String>msDS-GroupManagedServiceAccount</String>
                <String>msDS-ManagedServiceAccount</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
          <Attributes>
            <Map>
              <entry key="hidden">
                <value>
                  <Script>
                    <Source>
                          Object objType = field.getValue();    
                           if ("contact".equalsIgnoreCase(objType)) {
                              if (form.getSection("Dial-in") != null) {
                                  form.remove(form.getSection("Dial-in"));
                                  }
                              if (form.getSection("User Details") != null) {
                                  form.remove(form.getSection("User Details"));
                                  }
                              if (form.getSection("Skype for Business") != null) {
                                  form.remove(form.getSection("Skype for Business"));
                sio                  }
                              if (form.getSection("gmsa") != null) {
                                  form.remove(form.getSection("gmsa"));
                                  }

                              if (form.getSection("Exchange") != null &amp;&amp; form.getSection("Exchange").getFields() != null ) {
                                    for (Object field : form.getSection("Exchange").getFields()) {
                                         String name = field.getName();
                                         if (name != null &amp;&amp; name.indexOf(":") > 0 ) {
                                            String[] nameKeys = name.split(":");
                                              if (nameKeys.length > 1 &amp;&amp;
                                                  "homeMDB".equalsIgnoreCase(nameKeys[2])){
                                                  field.setHidden(true);
                                                }
                                            }
                                        }
                                 }  
                                     
                           }
                           else if ("msDS-GroupManagedServiceAccount".equalsIgnoreCase(objType)
                                    || "msDS-ManagedServiceAccount".equalsIgnoreCase(objType)) {
                            if (form.getSection("Dial-in") != null) {
                                form.remove(form.getSection("Dial-in"));
                            }
                            if (form.getSection("Skype for Business") != null) {
                                form.remove(form.getSection("Skype for Business"));
                            }
                            if (form.getSection("Exchange") != null) {
                                form.remove(form.getSection("Exchange"));
                            }
                            if (form.getSection("gmsa") != null) {
                                form.getSection("gmsa").setLabel("Service Account");
                            }

                            if (form.getSection("User Details") != null &amp;&amp; form.getSection("User Details").getFields() != null ) {
                                for (Object field : form.getSection("User Details").getFields()) {
                                    String name = field.getName();
                                    if (name != null &amp;&amp; name.indexOf(":") > 0 ) {
                                        String[] nameKeys = name.split(":");
                                        if (nameKeys.length > 1) {
                                            if("password".equalsIgnoreCase(nameKeys[2])
                                                    || "pwdLastSet".equalsIgnoreCase(nameKeys[2])
                                                    || "primaryGroupDN".equalsIgnoreCase(nameKeys[2]) )
                                            {
                                                field.setHidden(true);
                                            }
                                        }
                                    }
                                }
                            }
                            Object serviceAccSection = form.getSection("gmsa");
                            String dnsHostNameFieldName = null;
                            String pAllowedToRetrievPwdFieldName = null;
                            String pAllowedToDelegate = null;
                            String managePasswordInterval = null;

                            for (Object field : serviceAccSection.getFields()) {
                                String name = field.getName();
                                if( null != name) {
                                    if( name.contains(":dNSHostName"))
                                        dnsHostNameFieldName = name;
                                    else if( name.contains(":msDS-GroupMSAMembership") )
                                        pAllowedToRetrievPwdFieldName = name;
                                    else if( name.contains(":msDS-AllowedToActOnBehalfOfOtherIdentity") )
                                        pAllowedToDelegate = name;
                                    else if( name.contains(":msDS-ManagedPasswordInterval") )
                                        managePasswordInterval = name;
                                }
                            }
                            if ("msDS-GroupManagedServiceAccount".equalsIgnoreCase(objType))
                            {
                                if (null != dnsHostNameFieldName) {
                                    Object dnsHostName =   serviceAccSection.getField(dnsHostNameFieldName);
                                    dnsHostName.setRequired(true);
                                }
                            }
                            else if ("msDS-ManagedServiceAccount".equalsIgnoreCase(objType))
                            {
                                if (null != dnsHostNameFieldName) {
                                    Object dnsHostName =   serviceAccSection.getField(dnsHostNameFieldName);
                                    dnsHostName.setHidden(true);
                                }
                                if(null != pAllowedToRetrievPwdFieldName){
                                    Object msDSGroupMSAMembership = serviceAccSection.getField(pAllowedToRetrievPwdFieldName);
                                    msDSGroupMSAMembership.setHidden(true);
                                }
                                if(null != pAllowedToDelegate){
                                    Object PrincipalsAllowedToDelegate = serviceAccSection.getField(pAllowedToDelegate);
                                    PrincipalsAllowedToDelegate.setHidden(true);
                                }
                                if(null != managePasswordInterval) {
                                    Object ManageIntervalField = serviceAccSection.getField(managePasswordInterval);
                                    ManageIntervalField.setHidden(true);
                                }
                            }
                          }
                           else {
                                   if (form.getSection("User Details") != null &amp;&amp; form.getSection("User Details").getFields() != null ) {
                                      for (Object field : form.getSection("User Details").getFields()) {
                                         String name = field.getName();
                                         if (name != null &amp;&amp; name.indexOf(":") > 0 ) {
                                            String[] nameKeys = name.split(":");
                                              if (nameKeys.length > 1 &amp;&amp;
                                                  ("sAMAccountName".equalsIgnoreCase(nameKeys[2])
                                                 || "password".equalsIgnoreCase(nameKeys[2]))){
                                                  field.setRequired(true);
                                                }
                                            }
                                        }
                                     }
                                  if (form.getSection("gmsa") != null) {
                                     form.remove(form.getSection("gmsa"));
                                   }
                               }
                                 
                           return false;
                        </Source>
                  </Script>
                </value>
              </entry>
            </Map>
          </Attributes>
        </Field>
        <Field displayName="con_prov_policy_ad_distinguishedName" name="distinguishedName" section="Account" type="string">
          <RuleRef>
            <Reference class="sailpoint.object.Rule" id="c0a81db38c5d12ba818c630a20982f73" name="FieldValue-DN"/>
          </RuleRef>
        </Field>
      </Section>
      <Section label="User Details" name="User Details">
        <Field displayName="con_prov_policy_ad_sAMAccountName" helpKey="help_con_prov_policy_ad_sAMAccountName" name="sAMAccountName" section="User Details" type="string">
          <Script>
            <Source>String fname = identity.getFirstname();
String lname = identity.getLastname();

return fname.substring(0,3)+lname;</Source>
          </Script>
        </Field>
        <Field displayName="con_prov_policy_ad_password" helpKey="help_con_prov_policy_ad_password" name="password" section="User Details" type="string" value="Admin@123"/>
        <Field displayName="con_prov_policy_ad_pwdLastSet" helpKey="help_con_prov_policy_ad_pwdLastSet" name="pwdLastSet" section="User Details" type="boolean"/>
        <Field displayName="con_prov_policy_ad_IIQDisabled" helpKey="help_con_prov_policy_ad_IIQDisabled" name="IIQDisabled" section="User Details" type="boolean" value="false"/>
        <Field displayName="con_prov_policy_ad_primaryGroupDN" helpKey="help_con_prov_policy_ad_primaryGroupDN" name="primaryGroupDN" section="User Details" type="string"/>
      </Section>
      <Section label="General" name="General">
        <Field displayName="con_prov_policy_ad_givenName" helpKey="help_con_prov_policy_ad_givenName" name="givenName" section="General" type="string">
          <Script>
            <Source>return identity.getFirstname();</Source>
          </Script>
        </Field>
        <Field displayName="con_prov_policy_ad_sn" helpKey="help_con_prov_policy_ad_sn" name="sn" section="General" type="string">
          <Script>
            <Source>return identity.getLastname();</Source>
          </Script>
          <ValidationScript>
            <Source>return identity.getLastname();</Source>
          </ValidationScript>
        </Field>
        <Field displayName="mail" helpKey="help_con_prov_policy_ad_description" name="mail" section="General" type="string">
          <Script>
            <Source>return sAMAccountName+"@eshiam.com";</Source>
          </Script>
        </Field>
      </Section>
      <Section label="Dial-in" name="Dial-in">
        <Field displayName="con_prov_policy_ad_msNPAllowDialin" helpKey="help_con_prov_policy_ad_msNPAllowDialin" name="msNPAllowDialin" section="Dial-in" type="string" value="Not Set">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>Not Set</String>
                <String>true</String>
                <String>false</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
        </Field>
        <Field displayName="con_prov_policy_ad_msNPCallingStationID" helpKey="help_con_prov_policy_ad_msNPCallingStationID" multi="true" name="msNPCallingStationID" section="Dial-in" type="string"/>
        <Field displayName="con_prov_policy_ad_msRADIUSCallbackNumber" helpKey="help_con_prov_policy_ad_msRADIUSCallbackNumber" name="msRADIUSCallbackNumber" section="Dial-in" type="string"/>
        <Field displayName="con_prov_policy_ad_msRADIUSFramedRoute" helpKey="help_con_prov_policy_ad_msRADIUSFramedRoute" multi="true" name="msRADIUSFramedRoute" section="Dial-in" type="string"/>
        <Field displayName="con_prov_policy_ad_msRADIUSFramedIPAddress" helpKey="help_con_prov_policy_ad_msRADIUSFramedIPAddress" name="msRADIUSFramedIPAddress" section="Dial-in" type="string"/>
      </Section>
      <Section label="Exchange" name="Exchange">
        <Field displayName="con_prov_policy_ad_homeMDB" helpKey="help_con_prov_policy_ad_homeMDB" name="homeMDB" section="Exchange" type="string"/>
        <Field displayName="con_prov_policy_ad_mailNickname" helpKey="help_con_prov_policy_ad_mailNickname" name="mailNickname" section="Exchange" type="string"/>
        <Field displayName="con_prov_policy_ad_shadowAccountDN" helpKey="help_con_prov_policy_ad_shadowAccountDN" name="shadowAccountDN" section="Exchange" type="string"/>
        <Field displayName="con_prov_policy_ad_msExchHideFromAddressLists" helpKey="help_con_prov_policy_ad_msExchHideFromAddressLists" name="msExchHideFromAddressLists" section="Exchange" type="boolean"/>
        <Field displayName="con_prov_policy_ad_externalEmailAddress" helpKey="help_con_prov_policy_ad_externalEmailAddress" name="exch_externalEmailAddress" section="Exchange" type="string"/>
      </Section>
      <Section label="Skype for Business" name="Skype for Business">
        <Field displayName="con_prov_policy_ad_SipAddress" helpKey="help_con_prov_policy_ad_SipAddress" name="SipAddress" section="Skype for Business" type="string"/>
        <Field displayName="con_prov_policy_ad_SipDomain" helpKey="help_con_prov_policy_ad_SipDomain" name="SipDomain" section="Skype for Business" type="string"/>
        <Field displayName="con_prov_policy_ad_SipAddressType" helpKey="help_con_prov_policy_ad_SipAddressType" name="SipAddressType" section="Skype for Business" type="string">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>SamAccountName</String>
                <String>FirstLastName</String>
                <String>EmailAddress</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
        </Field>
        <Field displayName="con_prov_policy_ad_RegistrarPool" helpKey="help_con_prov_policy_ad_RegistrarPool" name="RegistrarPool" section="Skype for Business" type="string"/>
      </Section>
      <Section label="gmsa" name="gmsa">
        <Field displayName="con_prov_policy_ad_DNSHostName" helpKey="help_con_prov_policy_ad_DNSHostName" name="dNSHostName" section="gmsa" type="string"/>
        <Field displayName="con_prov_policy_ad_msDSSupportedEncryptionTypes" helpKey="help_con_prov_policy_ad_msDSSupportedEncryptionTypes" multi="true" name="msDS-SupportedEncryptionTypes" section="gmsa" type="string">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>DES</String>
                <String>RC4</String>
                <String>AES128</String>
                <String>AES256</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
        </Field>
        <Field displayName="con_prov_policy_ad_msDSManagedPasswordInterval" helpKey="help_con_prov_policy_ad_msDSManagedPasswordInterval" name="msDS-ManagedPasswordInterval" section="gmsa" type="string"/>
        <Field displayName="con_prov_policy_ad_msDSGroupMSAMembership" helpKey="help_con_prov_policy_ad_msDSGroupMSAMembership" multi="true" name="msDS-GroupMSAMembership" section="gmsa" type="string"/>
        <Field displayName="con_prov_policy_ad_msDSAllowedToActOnBehalfOfOtherIdentity" helpKey="help_con_prov_policy_ad_msDSAllowedToActOnBehalfOfOtherIdentity" multi="true" name="msDS-AllowedToActOnBehalfOfOtherIdentity" section="gmsa" type="string"/>
        <Field displayName="con_prov_policy_ad_ServicePrincipalNames" helpKey="help_con_prov_policy_ad_ServicePrincipalNames" multi="true" name="servicePrincipalName" section="gmsa" type="string"/>
      </Section>
    </Form>
    <Form name="Create Group" objectType="group" type="Create">
      <Attributes>
        <Map>
          <entry key="pageTitle" value="Create Group"/>
        </Map>
      </Attributes>
      <Section>
        <Field displayName="con_prov_policy_ad_distinguishedName_group" helpKey="help_con_prov_policy_ad_group_distinguishedName" name="distinguishedName" required="true" type="string"/>
        <Field displayName="con_prov_policy_ad_sAMAccountName" helpKey="help_con_prov_policy_ad_group_sAMAccountName" name="sAMAccountName" required="true" type="string"/>
      </Section>
    </Form>
    <Form name="Update Group" objectType="group" type="Update">
      <Attributes>
        <Map>
          <entry key="pageTitle" value="Update Group"/>
        </Map>
      </Attributes>
      <Section>
        <Field displayName="con_prov_policy_ad_GroupType" helpKey="help_con_prov_policy_ad_GroupType" name="GroupType" type="string" value="Security">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>Security</String>
                <String>Distribution</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
        </Field>
        <Field displayName="con_prov_policy_ad_GroupScope" helpKey="help_con_prov_policy_ad_GroupScope" name="GroupScope" type="string" value="Global">
          <AllowedValuesDefinition>
            <Value>
              <List>
                <String>Domain local</String>
                <String>Global</String>
                <String>Universal</String>
              </List>
            </Value>
          </AllowedValuesDefinition>
        </Field>
        <Field displayName="con_prov_policy_ad_description" helpKey="help_con_prov_policy_ad_group_description" name="description" type="string"/>
        <Field displayName="con_prov_policy_ad_mailNickname" helpKey="help_con_prov_policy_ad_group_mailNickname" name="mailNickname" type="string"/>
      </Section>
    </Form>
  </ProvisioningForms>
  <Schemas>
    <Schema created="1702468658111" displayAttribute="givenName" id="c0a81db38c5d12ba818c630a23bf2f76" identityAttribute="distinguishedName" instanceAttribute="" modified="1717563566419" nativeObjectType="User" objectType="account">
      <AttributeDefinition name="businessCategory" type="string">
        <Description>business category</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="carLicense" type="string">
        <Description>vehicle license or registration plate</Description>
      </AttributeDefinition>
      <AttributeDefinition name="cn" type="string">
        <Description>common name(s) for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="departmentNumber" type="string">
        <Description>identifies a department within an organization</Description>
      </AttributeDefinition>
      <AttributeDefinition name="description" type="string">
        <Description>descriptive information</Description>
      </AttributeDefinition>
      <AttributeDefinition name="destinationIndicator" type="string">
        <Description>destination indicator</Description>
      </AttributeDefinition>
      <AttributeDefinition name="displayName" type="string">
        <Description>preferred name to be used when displaying entries</Description>
      </AttributeDefinition>
      <AttributeDefinition name="distinguishedName" type="string">
        <Description>distinguished name for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="employeeNumber" type="string">
        <Description>numerically identifies an employee within an organization</Description>
      </AttributeDefinition>
      <AttributeDefinition name="employeeType" type="string">
        <Description>type of employment for a person</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="facsimileTelephoneNumber" type="string">
        <Description>Facsimile (Fax) Telephone Number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="givenName" type="string">
        <Description>first name(s) for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="homePhone" type="string">
        <Description>home telephone number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="homePostalAddress" type="string">
        <Description>home postal address</Description>
      </AttributeDefinition>
      <AttributeDefinition name="initials" type="string">
        <Description>initials of some or all of names, but not the surname(s).</Description>
      </AttributeDefinition>
      <AttributeDefinition name="internationalISDNNumber" type="string">
        <Description>international ISDN number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="l" type="string">
        <Description>city</Description>
      </AttributeDefinition>
      <AttributeDefinition name="mail" type="string">
        <Description>RFC822 Mailbox</Description>
      </AttributeDefinition>
      <AttributeDefinition name="manager" type="string">
        <Description>DN of manager</Description>
      </AttributeDefinition>
      <AttributeDefinition name="mobile" type="string">
        <Description>mobile telephone number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="o" type="string">
        <Description>organization this object belongs to</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="ou" type="string">
        <Description>organizational unit this object belongs to</Description>
      </AttributeDefinition>
      <AttributeDefinition name="pager" type="string">
        <Description>pager telephone number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="physicalDeliveryOfficeName" type="string">
        <Description>Physical Delivery Office Name</Description>
      </AttributeDefinition>
      <AttributeDefinition name="postOfficeBox" type="string">
        <Description>Post Office Box</Description>
      </AttributeDefinition>
      <AttributeDefinition name="postalAddress" type="string">
        <Description>postal address</Description>
      </AttributeDefinition>
      <AttributeDefinition name="postalCode" type="string">
        <Description>postal code</Description>
      </AttributeDefinition>
      <AttributeDefinition name="preferredDeliveryMethod" type="string">
        <Description>preferred delivery method</Description>
      </AttributeDefinition>
      <AttributeDefinition name="preferredLanguage" type="string">
        <Description>preferred written or spoken language for a person</Description>
      </AttributeDefinition>
      <AttributeDefinition name="registeredAddress" type="string">
        <Description>registered postal address</Description>
      </AttributeDefinition>
      <AttributeDefinition name="roomNumber" type="string">
        <Description>room number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="secretary" type="string">
        <Description>DN of secretary</Description>
      </AttributeDefinition>
      <AttributeDefinition name="seeAlso" type="string">
        <Description>DN of related object</Description>
      </AttributeDefinition>
      <AttributeDefinition name="sn" type="string">
        <Description>last (family) name(s) for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="st" type="string">
        <Description>state or province which this object resides in</Description>
      </AttributeDefinition>
      <AttributeDefinition name="street" type="string">
        <Description>street of this object</Description>
      </AttributeDefinition>
      <AttributeDefinition name="streetAddress" type="string">
        <Description>street address of this object</Description>
      </AttributeDefinition>
      <AttributeDefinition name="telephoneNumber" type="string">
        <Description>Telephone Number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="teletexTerminalIdentifier" type="string">
        <Description>Teletex Terminal Identifier</Description>
      </AttributeDefinition>
      <AttributeDefinition name="telexNumber" type="string">
        <Description>Telex Number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="title" type="string">
        <Description>title associated with the entity</Description>
      </AttributeDefinition>
      <AttributeDefinition name="uid" type="string">
        <Description>user identifier</Description>
      </AttributeDefinition>
      <AttributeDefinition name="userPrincipalName" type="string">
        <Description>user principal name</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="objectClass" type="string">
        <Description>object classes of the entity</Description>
      </AttributeDefinition>
      <AttributeDefinition entitlement="true" managed="true" multi="true" name="memberOf" schemaObjectType="group" type="string">
        <Description>Group Membership</Description>
      </AttributeDefinition>
      <AttributeDefinition name="objectSid" type="string">
        <Description>Windows Security Identifier</Description>
      </AttributeDefinition>
      <AttributeDefinition name="objectguid" type="string">
        <Description>Object globally unique identifier </Description>
      </AttributeDefinition>
      <AttributeDefinition name="objectType" type="string">
        <Description>Type of Active Directory object</Description>
      </AttributeDefinition>
      <AttributeDefinition name="sAMAccountName" type="string">
        <Description>sAMAccountName</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="accountFlags" type="string">
        <Description>List of the flags enabled on an account</Description>
      </AttributeDefinition>
      <AttributeDefinition name="department" type="string">
        <Description>User's department</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="msNPCallingStationID" type="string">
        <Description>CallingStationID</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="msRADIUSFramedRoute" type="string">
        <Description>Static Routes for Dial-In connection</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msNPAllowDialin" type="string">
        <Description>Is dial-in allowed</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msRADIUSCallbackNumber" type="string">
        <Description>Callback Number</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msRADIUSFramedIPAddress" type="string">
        <Description>Define Static IP Address</Description>
      </AttributeDefinition>
      <AttributeDefinition internalName="targetAddress" name="externalEmailAddress" type="string">
        <Description>External email address of Mail User</Description>
      </AttributeDefinition>
      <AttributeDefinition name="mailNickname" type="string">
        <Description>Exchange Alias</Description>
      </AttributeDefinition>
      <AttributeDefinition name="homeMDB" type="string">
        <Description>Exchange Database</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msExchHideFromAddressLists" type="string">
        <Description>Hide from Exchange address lists</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msRTCSIP-UserEnabled" type="boolean">
        <Description>User enabled for Skype for Business Server</Description>
      </AttributeDefinition>
      <AttributeDefinition name="SipAddress" type="string">
        <Description>Skype for Business sipAddress</Description>
      </AttributeDefinition>
      <AttributeDefinition name="RegistrarPool" type="string">
        <Description>Skype for Business Registrar pool</Description>
      </AttributeDefinition>
      <AttributeDefinition name="LyncPinSet" type="string">
        <Description>Skype for Business user pin set status</Description>
      </AttributeDefinition>
      <AttributeDefinition name="LyncPinLockedOut" type="string">
        <Description>Skype for Business user pin lock status</Description>
      </AttributeDefinition>
      <AttributeDefinition name="DialPlan" type="string">
        <Description>Skype for Business user dial plan name</Description>
      </AttributeDefinition>
      <AttributeDefinition name="dNSHostName" type="string">
        <Description>Fully Qualified Domain Name for the Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msDS-ManagedPasswordInterval" type="string">
        <Description>Password change interval in days for the Managed Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="msDS-SupportedEncryptionTypes" type="string">
        <Description>Supported Encryption Types for the Managed Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="msDS-GroupMSAMembership" type="string">
        <Description>Principals allowed to use Group Managed Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="msDS-AllowedToActOnBehalfOfOtherIdentity" type="string">
        <Description>Principals that can act on the behalf of Group Managed Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition multi="true" name="servicePrincipalName" type="string">
        <Description>Service principal names for the Service Account</Description>
      </AttributeDefinition>
      <AttributeDefinition name="shadowAccountDN" type="string">
        <Description>DistinguishedName of the Linked Mailbox shadow account</Description>
      </AttributeDefinition>
      <AttributeDefinition name="shadowAccountGuid" type="string">
        <Description>ObjectGuid of the Linked Mailbox shadow account</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msExchRecipientTypeDetails" type="string">
        <Description>Type of the Microsoft Exchange recipient object</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msDS-PrincipalName" type="string">
        <Description>Name of the entity in the format "NetBIOS domain name\sAMAccountName"</Description>
      </AttributeDefinition>
      <AttributeDefinition name="newEmail" type="string">
        <Description></Description>
      </AttributeDefinition>
    </Schema>
    <Schema created="1702468658111" descriptionAttribute="" displayAttribute="msDS-PrincipalName" featuresString="PROVISIONING, GROUPS_HAVE_MEMBERS" hierarchyAttribute="memberOf" id="c0a81db38c5d12ba818c630a23bf2f77" identityAttribute="distinguishedName" instanceAttribute="" modified="1717563566419" nativeObjectType="Group" objectType="group">
      <AttributeDefinition name="cn" type="string">
        <Description>common name(s) for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="distinguishedName" type="string">
        <Description>distinguished name for which the entity is known by</Description>
      </AttributeDefinition>
      <AttributeDefinition name="owner" type="string">
        <Description>owner (of the object)</Description>
      </AttributeDefinition>
      <AttributeDefinition name="description" type="string">
        <Description>descriptive information</Description>
      </AttributeDefinition>
      <AttributeDefinition entitlement="true" multi="true" name="memberOf" schemaObjectType="group" type="string">
        <Description>Group Membership</Description>
      </AttributeDefinition>
      <AttributeDefinition name="objectSid" type="string">
        <Description>Windows Security Identifier</Description>
      </AttributeDefinition>
      <AttributeDefinition name="objectguid" type="string">
        <Description>Object globally unique identifier </Description>
      </AttributeDefinition>
      <AttributeDefinition name="mailNickname" type="string">
        <Description>Exchange Distribution Group Name</Description>
      </AttributeDefinition>
      <AttributeDefinition name="GroupType" type="string">
        <Description>Group Type</Description>
      </AttributeDefinition>
      <AttributeDefinition name="GroupScope" type="string">
        <Description>Group Scope</Description>
      </AttributeDefinition>
      <AttributeDefinition name="sAMAccountName" type="string">
        <Description>sAMAccountName</Description>
      </AttributeDefinition>
      <AttributeDefinition name="msDS-PrincipalName" type="string">
        <Description>Name of the entity in the format "NetBIOS domain name\sAMAccountName"</Description>
      </AttributeDefinition>
      <Attributes>
        <Map>
          <entry key="groupMemberAttribute" value="member"/>
        </Map>
      </Attributes>
    </Schema>
  </Schemas>
  <ApplicationScorecard created="1702468658111" id="c0a81db38c5d12ba818c630a23bf2f75" modified="1717563566418"/>
</Application>
