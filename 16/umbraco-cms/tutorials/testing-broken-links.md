# Testing Links

## Valid link

- [Umbraco Homepage](https://umbraco.com/)  <!-- ✅ should pass -->

## Broken internal file

- [Missing File](16/umbraco-cms/fake-folder/missing.md)  <!-- ⚓ Anchor not found -->

## Broken anchor

- [Nonexistent Anchor](16/umbraco-cms/implementation/controllers.md#nonexistent-anchor)  <!-- ⚓ Anchor not found -->

## 404 external

- [Nonexistent Page](https://example.com/404-page)  <!-- ❌ 404 Not Found -->

## Redirected link

- [Redirect Example](http://github.com/)  <!-- 🔀 Redirect → http://github.com/ -->

## Timeout (simulate)

- [Timeout Example](http://10.255.255.1/)  <!-- ⏳ Timeout → ... -->
