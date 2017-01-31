ContextMenuItemAttribute
========================

```C#
public class Test_ContextMenuItemAttribute : MonoBehaviour
{
    [ContextMenuItemAttribute("menuItemName", "function")]
    [SerializeField]
    private string includeContextMenuItem;

    void function()
    {
        includeContextMenuItem = "Execute function";
    }
}
```

---

-	변수 우클릭 시 메뉴 노출

![df](/Unity/Image/ContextMenuItemAttribute_01.PNG)

---

-	function 실행 시

![df](/Unity/Image/ContextMenuItemAttribute_02.PNG)
