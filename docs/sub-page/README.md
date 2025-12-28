# DevHub Docs Importer Test Sub Page

## GitHub Alert Samples

This page demonstrates the five types of alerts available on GitHub (NOTE, TIP, IMPORTANT, WARNING, and CAUTION). Each alert includes various Markdown elements.

> [!NOTE]
> **About Basic Markdown Syntax**
>
> On GitHub, you can use the following basic Markdown syntax:
>
> - **Bold text**: `**bold**` or `__bold__`
> - *Italic text*: `*italic*` or `_italic_`
> - `Inline code`: Wrap with backticks
> - [Links](https://github.com): `[text](URL)`
>
> Example of a code block:
> ```bash
> git status
> git add .
> git commit -m "message"
> ```
>
> For more details, refer to the [GitHub documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

> [!TIP]
> **Performance Optimization Tips**
>
> To improve your application's performance, keep the following points in mind:
>
> 1. **Use caching**: Store frequently accessed data in cache
> 2. **Optimize database queries**:
>    - Set up indexes appropriately
>    - Use `JOIN` to avoid N+1 problems
>    - Don't fetch unnecessary data
> 3. **Use asynchronous processing**: Execute time-consuming operations asynchronously
>
> Example: Asynchronous processing in Node.js
> ```javascript
> async function fetchData() {
>   const data = await fetch('/api/data');
>   return data.json();
> }
> ```
>
> These optimizations can potentially **reduce response time by more than 50%**.

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

> [!IMPORTANT]
> **Required Security Settings**
>
> Before deploying your project to production, **make sure to verify the following settings**:
>
> - [ ] Sensitive information (API keys, passwords, etc.) is set in environment variables
> - [ ] HTTPS is enabled
> - [ ] Authentication and authorization mechanisms are properly implemented
> - [ ] SQL injection countermeasures are in place
>
> In particular, be careful not to commit `.env` files to your Git repository:
> ```bash
> # Add to .gitignore
> .env
> .env.local
> .env.*.local
> ```
>
> Neglecting these settings may result in **serious security risks**.

At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga.

Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus.

> [!WARNING]
> **Database Operation Warnings**
>
> When performing the following operations, **always take a backup** first:
>
> - Executing `DROP TABLE` commands
> - Deleting large amounts of data with `DELETE` queries
> - Schema changes (`ALTER TABLE`)
> - Running migrations in production
>
> Example of a dangerous operation:
> ```sql
> -- ⚠️ This operation cannot be undone!
> DELETE FROM users WHERE created_at < '2020-01-01';
> ```
>
> If executed by mistake, **data recovery may be difficult**. Always verify the target data with a `SELECT` statement before performing the operation.

Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

> [!CAUTION]
> **About Using Deprecated APIs**
>
> The following APIs are **deprecated** and will be removed in future versions:
>
> - `oldFunction()` → Use `newFunction()` instead
> - `deprecatedMethod()` → Migrate to `modernMethod()`
>
> Code using deprecated APIs:
> ```javascript
> // ⚠️ Deprecated: This code may stop working
> const result = oldFunction(data);
> ```
>
> Recommended approach:
> ```javascript
> // ✅ Recommended: Use the new API
> const result = newFunction(data);
> ```
>
> Continuing to use these APIs may result in **your application ceasing to function**. We recommend migrating as soon as possible.

Sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur.

Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur. At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident.
