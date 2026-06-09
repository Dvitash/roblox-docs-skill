# EditableMesh

**Superclass:** [Object](Object.md)

### EditableMesh Class - The `EditableMesh` class is used to allow for the runtime creation and manipulation of meshes within a `Class.MeshPart`. - It provides methods for querying and modifying the mesh when linked to a `Class.MeshPart`. ### Enabling and Security - **Default Usage:** By default, `EditableMesh` fails by default for published experiences; users must be 13+ years old or ID verified to use it. - **Security Trigger:** To enable usage, the user must be 13+ years old and ID verified…

## Tags
- NotCreatable

## Properties
### `EditableMesh.FixedSize`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns `true` if a mesh is fixed-size.

## Methods
### `EditableMesh:AddBone(boneProperties: Dictionary) -> int64`
- **Summary:** Adds a new bone and returns a stable bone ID.

### `EditableMesh:AddColor(color: Color3, alpha: float) -> int64`
- **Summary:** Adds a new color to the geometry and returns a stable color ID.

### `EditableMesh:AddNormal(normal: Vector3?) -> int64`
- **Summary:** Adds a new normal to the geometry and returns a stable normal ID.

### `EditableMesh:AddTriangle(vertexId0: int64, vertexId1: int64, vertexId2: int64) -> int64`
- **Summary:** Adds a new triangle to the mesh and returns a stable face ID.

### `EditableMesh:AddUV(uv: Vector2) -> int64`
- **Summary:** Adds a new UV to the geometry and returns a stable UV ID.

### `EditableMesh:AddVertex(p: Vector3) -> int64`
- **Summary:** Adds a new vertex to the geometry and returns a stable vertex ID.

### `EditableMesh:Destroy() -> ()`
- **Summary:** Destroys the mesh.

### `EditableMesh:FindClosestPointOnSurface(point: Vector3) -> Tuple`
- **Summary:** Finds the closest point on the mesh's surface.

### `EditableMesh:FindClosestVertex(toThisPoint: Vector3) -> int64`
- **Summary:** Finds the closest vertex to a specific point in space.

### `EditableMesh:FindVerticesWithinSphere(center: Vector3, radius: float) -> Array`
- **Summary:** Finds all vertices within a specific sphere.

### `EditableMesh:GetAdjacentFaces(faceId: int64) -> Array`
- **Summary:** Returns a list of faces adjacent to a given face.

### `EditableMesh:GetAdjacentVertices(vertexId: int64) -> Array`
- **Summary:** Returns a list of vertices adjacent to a given vertex.

### `EditableMesh:GetBoneByName(boneName: string) -> int64`
- **Summary:** Finds the bone ID of the bone with the given name.

### `EditableMesh:GetBoneCFrame(boneId: int64) -> CFrame`
- **Summary:** Returns the initial `Datatype.CFrame` of the bone in the bind pose of the mesh.

### `EditableMesh:GetBoneIsVirtual(boneId: int64) -> boolean`
- **Summary:** Returns `true` if the bone is virtual.

### `EditableMesh:GetBoneName(boneId: int64) -> string`
- **Summary:** Returns the bone name.

### `EditableMesh:GetBoneParent(boneId: int64) -> int64`
- **Summary:** Returns the parent bone ID, if any.

### `EditableMesh:GetBones() -> Array`
- **Summary:** Returns all bones of the mesh.

### `EditableMesh:GetCenter() -> Vector3`

### `EditableMesh:GetColor(colorId: int64) -> Color3?`
- **Summary:** Returns the color for the given color ID.

### `EditableMesh:GetColorAlpha(colorId: int64) -> float?`
- **Summary:** Returns the color alpha (transparency) at the given color ID.

### `EditableMesh:GetColors() -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns all colors of the mesh.

### `EditableMesh:GetFaceColors(faceId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the face's color IDs for the vertices on the face.

### `EditableMesh:GetFaceNormals(faceId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the face's normal IDs for the vertices on the face.

### `EditableMesh:GetFaces() -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns all faces of the mesh.

### `EditableMesh:GetFacesWithAttribute(id: int64) -> Array`
- **Tags:** Deprecated
- **Summary:** Returns a list of faces that use a given attribute ID.

### `EditableMesh:GetFacesWithColor(colorId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of face IDs that use the given color ID.

### `EditableMesh:GetFacesWithNormal(normalId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of face IDs that use the given normal ID.

### `EditableMesh:GetFacesWithUV(uvId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of face IDs that use the given UV ID.

### `EditableMesh:GetFaceUVs(faceId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the face's UV IDs for the vertices on the face.

### `EditableMesh:GetFaceVertices(faceId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the face's vertex IDs.

### `EditableMesh:GetFacsCorrectivePose(actions: Array) -> Tuple`
- **Summary:** Returns bone IDs and bone `Datatype.CFrame|CFrames` for all bones in a specific FACS corrective pose.

### `EditableMesh:GetFacsCorrectivePoses() -> Array`
- **Summary:** Returns all FACS corrective poses that are in use.

### `EditableMesh:GetFacsPose(action: FacsActionUnit) -> Tuple`
- **Summary:** Returns bone IDs and bone `Datatype.CFrame|CFrames` for all bones in a specific FACS action unit.

### `EditableMesh:GetFacsPoses() -> Array`
- **Summary:** Returns all FACS action units that have poses defined.

### `EditableMesh:GetNormal(normalId: int64) -> Vector3?`
- **Summary:** Returns the normal vector for the given normal ID.

### `EditableMesh:GetNormals() -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns all normals of the mesh.

### `EditableMesh:GetPosition(vertexId: int64) -> Vector3`
- **Summary:** Gets the position of a vertex.

### `EditableMesh:GetSize() -> Vector3`

### `EditableMesh:GetUV(uvId: int64) -> Vector2?`
- **Summary:** Returns UV coordinates at the given UV ID.

### `EditableMesh:GetUVs() -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns all UVs of the mesh.

### `EditableMesh:GetVertexBones(vertexId: int64) -> Array`
- **Summary:** Returns all bone IDs that are associated with the vertex for skinning.

### `EditableMesh:GetVertexBoneWeights(vertexId: int64) -> Array`
- **Summary:** Returns skinning blend weights for each bone that is associated with the vertex.

### `EditableMesh:GetVertexColors(vertexId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the color IDs of the faces attached to the given vertex.

### `EditableMesh:GetVertexFaceColor(vertexId: int64, faceId: int64) -> int64`
- **Summary:** Returns the color ID of a vertex/face pair.

### `EditableMesh:GetVertexFaceNormal(vertexId: int64, faceId: int64) -> int64`
- **Summary:** Returns the normal ID of a vertex/face pair.

### `EditableMesh:GetVertexFaces(vertexId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the face IDs of the faces attached to the given vertex.

### `EditableMesh:GetVertexFaceUV(vertexId: int64, faceId: int64) -> int64`
- **Summary:** Returns the UV ID of a vertex/face pair.

### `EditableMesh:GetVertexNormals(vertexId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the normal IDs of the faces attached to the given vertex.

### `EditableMesh:GetVertexUVs(vertexId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns the UV IDs of the faces attached to the given vertex.

### `EditableMesh:GetVertices() -> Array`
- **Summary:** Returns all vertices as a list of stable vertex IDs.

### `EditableMesh:GetVerticesWithAttribute(id: int64) -> Array`
- **Tags:** Deprecated
- **Summary:** Returns a list of vertices that use a given attribute ID.

### `EditableMesh:GetVerticesWithColor(colorId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of vertex IDs that use the given color ID.

### `EditableMesh:GetVerticesWithNormal(normalId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of vertex IDs that use the given normal ID.

### `EditableMesh:GetVerticesWithUV(uvId: int64) -> Array`
- **Tags:** CustomLuaState
- **Summary:** Returns an array of vertex IDs that use the given UV ID.

### `EditableMesh:IdDebugString(id: int64) -> string`
- **Summary:** Returns a string describing a stable ID, useful for debugging purposes.

### `EditableMesh:MergeVertices(mergeTolerance: float) -> Map`
- **Summary:** Merges vertices that touch together.

### `EditableMesh:RaycastLocal(origin: Vector3, direction: Vector3) -> Tuple`

### `EditableMesh:RemoveBone(boneId: int64) -> ()`
- **Summary:** Removes a bone using its stable bone ID.

### `EditableMesh:RemoveFace(faceId: int64) -> ()`
- **Summary:** Removes a face using its stable face ID.

### `EditableMesh:RemoveUnused() -> Array`
- **Summary:** Removes all unused vertices, normals, UVs, and colors, and returns the removed IDs.

### `EditableMesh:ResetNormal(normalId: int64) -> ()`
- **Summary:** Reset this normal ID to be automatically calculated.

### `EditableMesh:SetBoneCFrame(boneId: int64, cframe: CFrame) -> ()`
- **Summary:** Set the initial `Datatype.CFrame` for a bone in the mesh's bind pose.

### `EditableMesh:SetBoneIsVirtual(boneId: int64, virtual: boolean) -> ()`
- **Summary:** Set whether a bone is virtual.

### `EditableMesh:SetBoneName(boneId: int64, name: string) -> ()`
- **Summary:** Sets the name for a bone.

### `EditableMesh:SetBoneParent(boneId: int64, parentBoneId: int64) -> ()`
- **Summary:** Set a parent for a bone.

### `EditableMesh:SetColor(colorId: int64, color: Color3) -> ()`
- **Summary:** Sets the color for a color ID.

### `EditableMesh:SetColorAlpha(colorId: int64, alpha: float) -> ()`
- **Summary:** Sets the color alpha (transparency) for a color ID.

### `EditableMesh:SetFaceColors(faceId: int64, ids: Array) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the face's vertex colors to new color IDs.

### `EditableMesh:SetFaceNormals(faceId: int64, ids: Array) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the face's vertex normals to new normal IDs.

### `EditableMesh:SetFaceUVs(faceId: int64, ids: Array) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the face's vertex UVs to new UV IDs.

### `EditableMesh:SetFaceVertices(faceId: int64, ids: Array) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Sets the face's vertices to new vertex IDs.

### `EditableMesh:SetFacsBonePose(action: FacsActionUnit, boneId: int64, cframe: CFrame) -> ()`
- **Summary:** Set `Datatype.CFrame` for an individual bone in a specific FACS action unit.

### `EditableMesh:SetFacsCorrectivePose(actions: Array, boneIds: Array, cframes: Array) -> ()`
- **Summary:** Set pose for all bones in a specific FACS corrective pose.

### `EditableMesh:SetFacsPose(action: FacsActionUnit, boneIds: Array, cframes: Array) -> ()`
- **Summary:** Set pose for all bones in a specific FACS action unit.

### `EditableMesh:SetNormal(normalId: int64, normal: Vector3) -> ()`
- **Summary:** Set the normal for a normal ID.

### `EditableMesh:SetPosition(vertexId: int64, p: Vector3) -> ()`
- **Summary:** Sets a vertex position in the mesh's local object space.

### `EditableMesh:SetUV(uvId: int64, uv: Vector2) -> ()`
- **Summary:** Sets UV coordinates for a UV ID.

### `EditableMesh:SetVertexBones(vertexId: int64, boneIDs: Array) -> ()`
- **Summary:** Assign a list of bones with the vertex for skinning.

### `EditableMesh:SetVertexBoneWeights(vertexId: int64, boneWeights: Array) -> ()`
- **Summary:** Sets skinning blend weights for each bone associated with the vertex.

### `EditableMesh:SetVertexFaceColor(vertexId: int64, faceId: int64, colorId: int64) -> ()`
- **Summary:** Sets the color ID of a vertex/face pair.

### `EditableMesh:SetVertexFaceNormal(vertexId: int64, faceId: int64, normalId: int64) -> ()`
- **Summary:** Sets the normal ID of a vertex/face pair.

### `EditableMesh:SetVertexFaceUV(vertexId: int64, faceId: int64, uvId: int64) -> ()`
- **Summary:** Sets the UV ID of a vertex/face pair.

### `EditableMesh:Triangulate() -> ()`
- **Summary:** Splits all faces on the mesh to be triangles.
