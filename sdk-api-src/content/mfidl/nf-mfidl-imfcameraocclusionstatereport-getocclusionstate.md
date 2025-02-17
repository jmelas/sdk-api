---
UID: NF:mfidl.IMFCameraOcclusionStateReport.GetOcclusionState
tech.root: 
title: IMFCameraOcclusionStateReport::GetOcclusionState
ms.date: 
targetos: Windows
description: 
prerelease: true
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: mfidl.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - mfidl.h
api_name:
 - IMFCameraOcclusionStateReport::GetOcclusionState
f1_keywords:
 - IMFCameraOcclusionStateReport::GetOcclusionState
 - mfidl/IMFCameraOcclusionStateReport::GetOcclusionState
dev_langs:
 - c++
---

## -description

Gets the camera occlusion state associated with the occlusion state report.

## -parameters

### -param occlusionState

A **DWORD** output parameter containing a value from the [MFCameraOcclusionState](ne-mfidl-mfcameraocclusionstate.md) enumeration.

## -returns

| Error code | Description |
|------------|-------------|
| S_OK    | Succeeded |
| E_INVALIDARG | *occlusionState* is nullptr. |

## -remarks

## -see-also

[MFCameraOcclusionState](ne-mfidl-mfcameraocclusionstate.md)

