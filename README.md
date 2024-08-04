# ModifyReadWrite

This script provides a menu item in the Unity Editor to toggle the 'm_IsReadable' property in selected assets.
Some meshes could not be edited so I made a version that works on every mesh. Link below
https://github.com/heartingNinja/MeshReadWriteToggle
Used this doc
https://docs.unity3d.com/ScriptReference/Mesh.UploadMeshData.html

## How to Use

### Toggle Read/Write

This menu item toggles the 'm_IsReadable' property of the selected assets.

1. Select the assets you want to modify in the Unity Editor.
2. Click on any of the selected assets in the Project window.
3. Navigate to `Assets > Toggle Read/Write`.
4. The 'm_IsReadable' property of the selected assets will be toggled between `true` and `false`.

## Notes

- This script assumes that the 'm_IsReadable' property is present in the text content of the assets.
- Make sure to have a backup of your assets before running the modification.

## License

This project is licensed under the [MIT License](LICENSE).
