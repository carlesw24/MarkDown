# MarkDown

![imagen](https://www.shutterstock.com/image-illustration/coding-programming-developing-typing-script-600nw-2258898245.jpg)

### ¿Qué es YAML?
YAML es un lenguaje de serialización de datos que las personas pueden comprender y suele utilizarse en el diseño de archivos de configuración. Para algunas personas, YAML significa otro lenguaje de marcado más; para otras, es un acrónimo recursivo que quiere decir "YAML no es un lenguaje de marcado", lo que enfatiza la idea de que se utiliza para los datos, no para los documentos.

### Sintaxis de YAML

YAML utiliza una extensión de archivos .yml o .yaml y sigue reglas de sintaxis específicas. 

Tiene características que provienen de Perl, C, XML, HTML y otros lenguajes de programación. También se basa en JSON, por lo que los archivos JSON son compatibles con YAML.

### Los usos de YAML

Uno de los usos más comunes es la creación de archivos de configuración. Se recomienda utilizar YAML en lugar de JSON para escribir los archivos de configuración porque es un lenguaje más fácil de comprender, aunque ambos pueden usarse de manera indistinta en la mayoría de los casos.

### Ejemplo de código YAML [ejemplo](https://docs.unity3d.com/es/2018.4/Manual/YAMLSceneExample.html).
    
            %YAML 1.1
            %TAG !u! tag:unity3d.com,2011:
            --- !u!header
            SerializedFile:
            m_TargetPlatform: 4294967294
            m_UserInformation: 
            --- !u!29 &1
            Scene:
            m_ObjectHideFlags: 0
            m_PVSData: 
            m_QueryMode: 1
            m_PVSObjectsArray: []
            m_PVSPortalsArray: []
            m_ViewCellSize: 1.000000
            --- !u!104 &2
            RenderSettings:
            m_Fog: 0
            m_FogColor: {r: 0.500000, g: 0.500000, b: 0.500000, a: 1.000000}
            m_FogMode: 3
            m_FogDensity: 0.010000
            m_LinearFogStart: 0.000000
            m_LinearFogEnd: 300.000000
            m_AmbientLight: {r: 0.200000, g: 0.200000, b: 0.200000, a: 1.000000}
            m_SkyboxMaterial: {fileID: 0}
            m_HaloStrength: 0.500000
            m_FlareStrength: 1.000000
            m_HaloTexture: {fileID: 0}
            m_SpotCookie: {fileID: 0}
            m_ObjectHideFlags: 0
            --- !u!127 &3
            GameManager:
            m_ObjectHideFlags: 0
            --- !u!157 &4
            LightmapSettings:
            m_ObjectHideFlags: 0
            m_LightProbeCloud: {fileID: 0}
            m_Lightmaps: []
            m_LightmapsMode: 1
            m_BakedColorSpace: 0
            m_UseDualLightmapsInForward: 0
            m_LightmapEditorSettings:
            m_Resolution: 50.000000
            m_LastUsedResolution: 0.000000
            m_TextureWidth: 1024
            m_TextureHeight: 1024
            m_BounceBoost: 1.000000
            m_BounceIntensity: 1.000000
            m_SkyLightColor: {r: 0.860000, g: 0.930000, b: 1.000000, a: 1.000000}
            m_SkyLightIntensity: 0.000000
            m_Quality: 0
            m_Bounces: 1
            m_FinalGatherRays: 1000
            m_FinalGatherContrastThreshold: 0.050000
            m_FinalGatherGradientThreshold: 0.000000
            m_FinalGatherInterpolationPoints: 15
            m_AOAmount: 0.000000
            m_AOMaxDistance: 0.100000
            m_AOContrast: 1.000000
            m_TextureCompression: 0
            m_LockAtlas: 0
            --- !u!196 &5
            NavMeshSettings:
            m_ObjectHideFlags: 0
            m_BuildSettings:
            cellSize: 0.200000
            cellHeight: 0.100000
            agentSlope: 45.000000
            agentClimb: 0.900000
            ledgeDropHeight: 0.000000
            maxJumpAcrossDistance: 0.000000
            agentRadius: 0.400000
            agentHeight: 1.800000
            maxEdgeLength: 12
            maxSimplificationError: 1.300000
            regionMinSize: 8
            regionMergeSize: 20
            tileSize: 500
            detailSampleDistance: 6.000000
            detailSampleMaxError: 1.000000
            accuratePlacement: 0
            m_NavMesh: {fileID: 0}
            --- !u!1 &6
            GameObject:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            importerVersion: 3
            m_Component:
            - 4: {fileID: 8}
            - 33: {fileID: 12}
            - 65: {fileID: 13}
            - 23: {fileID: 11}
            m_Layer: 0
            m_Name: Cube
            m_TagString: Untagged
            m_Icon: {fileID: 0}
            m_NavMeshLayer: 0
            m_StaticEditorFlags: 0
            m_IsActive: 1
            --- !u!1 &7
            GameObject:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            importerVersion: 3
            m_Component:
            - 4: {fileID: 9}
            - 20: {fileID: 10}
            - 92: {fileID: 15}
            - 124: {fileID: 16}
            - 81: {fileID: 14}
            m_Layer: 0
            m_Name: Main Camera
            m_TagString: MainCamera
            m_Icon: {fileID: 0}
            m_NavMeshLayer: 0
            m_StaticEditorFlags: 0
            m_IsActive: 1
            --- !u!4 &8
            Transform:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 6}
            m_LocalRotation: {x: 0.000000, y: 0.000000, z: 0.000000, w: 1.000000}
            m_LocalPosition: {x: -2.618721, y: 1.028581, z: 1.131627}
            m_LocalScale: {x: 1.000000, y: 1.000000, z: 1.000000}
            m_Children: []
            m_Father: {fileID: 0}
            --- !u!4 &9
            Transform:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 7}
            m_LocalRotation: {x: 0.000000, y: 0.000000, z: 0.000000, w: 1.000000}
            m_LocalPosition: {x: 0.000000, y: 1.000000, z: -10.000000}
            m_LocalScale: {x: 1.000000, y: 1.000000, z: 1.000000}
            m_Children: []
            m_Father: {fileID: 0}
            --- !u!20 &10
            Camera:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 7}
            m_Enabled: 1
            importerVersion: 2
            m_ClearFlags: 1
            m_BackGroundColor: {r: 0.192157, g: 0.301961, b: 0.474510, a: 0.019608}
            m_NormalizedViewPortRect:
            importerVersion: 2
            x: 0.000000
            y: 0.000000
            width: 1.000000
            height: 1.000000
            near clip plane: 0.300000
            far clip plane: 1000.000000
            field of view: 60.000000
            orthographic: 0
            orthographic size: 100.000000
            m_Depth: -1.000000
            m_CullingMask:
            importerVersion: 2
            m_Bits: 4294967295
            m_RenderingPath: -1
            m_TargetTexture: {fileID: 0}
            m_HDR: 0
            --- !u!23 &11
            Renderer:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 6}
            m_Enabled: 1
            m_CastShadows: 1
            m_ReceiveShadows: 1
            m_LightmapIndex: 255
            m_LightmapTilingOffset: {x: 1.000000, y: 1.000000, z: 0.000000, w: 0.000000}
            m_Materials:
            - {fileID: 10302, guid: 0000000000000000e000000000000000, type: 0}
            m_SubsetIndices: 
            m_StaticBatchRoot: {fileID: 0}
            m_LightProbeAnchor: {fileID: 0}
            m_UseLightProbes: 0
            m_ScaleInLightmap: 1.000000
            --- !u!33 &12
            MeshFilter:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 6}
            m_Mesh: {fileID: 10202, guid: 0000000000000000e000000000000000, type: 0}
            --- !u!65 &13
            BoxCollider:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 6}
            m_Material: {fileID: 0}
            m_IsTrigger: 0
            m_Enabled: 1
            importerVersion: 2
            m_Size: {x: 1.000000, y: 1.000000, z: 1.000000}
            m_Center: {x: 0.000000, y: 0.000000, z: 0.000000}
            --- !u!81 &14
            AudioListener:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 7}
            m_Enabled: 1
            --- !u!92 &15
            Behaviour:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 7}
            m_Enabled: 1
            --- !u!124 &16
            Behaviour:
            m_ObjectHideFlags: 0
            m_PrefabParentObject: {fileID: 0}
            m_PrefabInternal: {fileID: 0}
            m_GameObject: {fileID: 7}
            m_Enabled: 1
            --- !u!1026 &17
            HierarchyState:
            m_ObjectHideFlags: 0
            expanded: []
            selection: []
            scrollposition_x: 0.000000
            scrollposition_y: 0.000000

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### ¿ Qué es JSON?

Se trata de un formato para guardar e intercambiar información que cualquier persona pueda leer. Los archivos json contienen solo texto y usan la extensión .json.

### Sintaxis JSON

Hay dos elementos centrales en un objeto JSON: claves (Keys) y valores (Values).

* Las Keys deben ser cadenas de caracteres (strings). Como su nombre en español lo indica, estas contienen una secuencia de caracteres rodeados de comillas.
* Los Values son un tipo de datos JSON válido. Puede tener la forma de un arreglo (array), objeto, cadena (string), booleano, número o nulo.


Un objeto JSON comienza y termina con llaves {}. Puede tener dos o más pares de claves/valor dentro, con una coma para separarlos. Así mismo, cada key es seguida por dos puntos para distinguirla del valor.

### Ejemplo JSON [ejemplo](https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=957:ejemplos-json-archivo-datos-cambio-formato-convertidor-on-line-xml-a-json-y-al-reves-minificar-cu01214f&catid=83&Itemid=212)
    {
        "marcadores": [
          {
            "latitude": 40.416875,
            "longitude": -3.703308,
            "city": "Madrid",
            "description": "Puerta del Sol"
          },
          {
            "latitude": 40.417438,
            "longitude": -3.693363,
            "city": "Madrid",
            "description": "Paseo del Prado"
          },
          {
            "latitude": 40.407015,
            "longitude": -3.691163,
            "city": "Madrid",
            "description": "Estación de Atocha"
          }
        ]
    }

# Webgarfía

### [YAML](https://docs.unity3d.com/es/2018.4/Manual/YAMLSceneExample.html)
### [JSON](https://www.hostinger.es/tutoriales/que-es-json)
