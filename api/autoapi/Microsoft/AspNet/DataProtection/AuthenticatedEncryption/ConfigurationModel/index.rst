

Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel Namespace
====================================================================================







.. toctree::
   :hidden:
   :maxdepth: 2

   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/AuthenticatedEncryptorConfiguration/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/AuthenticatedEncryptorDescriptor/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/AuthenticatedEncryptorDescriptorDeserializer/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngCbcAuthenticatedEncryptorConfiguration/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngCbcAuthenticatedEncryptorDescriptor/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngCbcAuthenticatedEncryptorDescriptorDeserializer/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngGcmAuthenticatedEncryptorConfiguration/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngGcmAuthenticatedEncryptorDescriptor/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/CngGcmAuthenticatedEncryptorDescriptorDeserializer/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/IAuthenticatedEncryptorConfiguration/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/IAuthenticatedEncryptorDescriptor/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/IAuthenticatedEncryptorDescriptorDeserializer/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/ManagedAuthenticatedEncryptorConfiguration/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/ManagedAuthenticatedEncryptorDescriptor/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/ManagedAuthenticatedEncryptorDescriptorDeserializer/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/XmlExtensions/index
   
   
   
   /autoapi/Microsoft/AspNet/DataProtection/AuthenticatedEncryption/ConfigurationModel/XmlSerializedDescriptorInfo/index
   
   











.. dn:namespace:: Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel


    .. rubric:: Classes


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.AuthenticatedEncryptorConfiguration`
        Represents a generalized authenticated encryption mechanism.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.AuthenticatedEncryptorDescriptor`
        A descriptor which can create an authenticated encryption system based upon the
        configuration provided by an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.AuthenticatedEncryptionOptions` object.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.AuthenticatedEncryptorDescriptorDeserializer`
        A class that can deserialize an :any:`System.Xml.Linq.XElement` that represents the serialized version
        of an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.AuthenticatedEncryptorDescriptor`\.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngCbcAuthenticatedEncryptorConfiguration`
        Represents a configured authenticated encryption mechanism which uses
        Windows CNG algorithms in CBC encryption + HMAC authentication modes.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngCbcAuthenticatedEncryptorDescriptor`
        A descriptor which can create an authenticated encryption system based upon the
        configuration provided by an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.CngCbcAuthenticatedEncryptionOptions` object.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngCbcAuthenticatedEncryptorDescriptorDeserializer`
        A class that can deserialize an :any:`System.Xml.Linq.XElement` that represents the serialized version
        of an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngCbcAuthenticatedEncryptorDescriptor`\.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngGcmAuthenticatedEncryptorConfiguration`
        Represents a configured authenticated encryption mechanism which uses
        Windows CNG algorithms in GCM encryption + authentication modes.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngGcmAuthenticatedEncryptorDescriptor`
        A descriptor which can create an authenticated encryption system based upon the
        configuration provided by an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.CngGcmAuthenticatedEncryptionOptions` object.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngGcmAuthenticatedEncryptorDescriptorDeserializer`
        A class that can deserialize an :any:`System.Xml.Linq.XElement` that represents the serialized version
        of an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.CngGcmAuthenticatedEncryptorDescriptor`\.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.ManagedAuthenticatedEncryptorConfiguration`
        Represents a configured authenticated encryption mechanism which uses
        managed SymmetricAlgorithm and KeyedHashAlgorithm types.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.ManagedAuthenticatedEncryptorDescriptor`
        A descriptor which can create an authenticated encryption system based upon the
        configuration provided by an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ManagedAuthenticatedEncryptionOptions` object.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.ManagedAuthenticatedEncryptorDescriptorDeserializer`
        A class that can deserialize an :any:`System.Xml.Linq.XElement` that represents the serialized version
        of an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.ManagedAuthenticatedEncryptorDescriptor`\.


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.XmlExtensions`
        


    class :dn:cls:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.XmlSerializedDescriptorInfo`
        Wraps an :any:`System.Xml.Linq.XElement` that contains the XML-serialized representation of an 
        :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.IAuthenticatedEncryptorDescriptor` along with the type that can be used
        to deserialize it.


    .. rubric:: Interfaces


    interface :dn:iface:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.IAuthenticatedEncryptorConfiguration`
        The basic configuration that serves as a factory for types related to authenticated encryption.


    interface :dn:iface:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.IAuthenticatedEncryptorDescriptor`
        A self-contained descriptor that wraps all information (including secret key
        material) necessary to create an instance of an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.IAuthenticatedEncryptor`\.


    interface :dn:iface:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.IAuthenticatedEncryptorDescriptorDeserializer`
        The basic interface for deserializing an XML element into an :any:`Microsoft.AspNet.DataProtection.AuthenticatedEncryption.ConfigurationModel.IAuthenticatedEncryptorDescriptor`\.


