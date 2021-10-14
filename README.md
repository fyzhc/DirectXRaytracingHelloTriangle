# 基于DirectX 12 实现的光线追踪  三角形 demo
# 本demo要求显卡支持dx12光追
# 根据NVIDIA官方[教程](https://developer.nvidia.com/rtx/raytracing/dxr/dx12-raytracing-tutorial-part-1)实现的demo
官方也提供了完整的[实现](https://developer.nvidia.com/rtx/raytracing/dxr/tutorial/Files/DXRTutorial_Extra.zip)，只不过下载下来不能直接运行，
因为官方教程是根据微软官方[示例](https://github.com/microsoft/DirectX-Graphics-Samples/tree/master/Samples/Desktop/D3D12Raytracing)开发的，但是没有附带dxcompile.dll和dxil.dll文件，
这里为了方便下载下来可以直接看效果，就把它们放到一起了。并且也对官方demo优化了字节对齐的问题，不然会输出警告。
