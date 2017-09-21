# educationSubmissionResource resource type

Wrapper around resource for used on a submission.  The wrapper adds a pointer to the assignment resource if this was copied from the assignment.  


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get educationSubmissionResource](../api/educationsubmissionresource_get.md) | [educationSubmissionResource](educationsubmissionresource.md) |Read properties and relationships of educationSubmissionResource object.|
|[Delete](../api/educationsubmissionresource_delete.md) | None |Delete educationSubmissionResource object. |

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|assignmentResource|[educationODataRef](educationodataref.md)|Pointer to the assignment from which this resource was copied.  If this is null, the student uploaded the resource.|
|id|String| Read-only.|
|resource|[educationResource](educationresource.md)|Resource object.|

## Relationships
None


## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationSubmissionResource"
}-->

```json
{
  "assignmentResource": {"@odata.type": "microsoft.graph.educationODataRef"},
  "id": "String (identifier)",
  "resource": {"@odata.type": "microsoft.graph.educationResource"}
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "educationSubmissionResource resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->