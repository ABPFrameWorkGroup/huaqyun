<<<<<<< HEAD
# Headline

# Cover

Activate the cover feature by setting `coverpage` to **true**, compare [coverpage configuration](configuration.md#coverpage).

## Basic usage

Set `coverpage` to **true**, and create a `_coverpage.md`:

```html
<!-- index.html1 -->

<script>
  window.$docsify = {
    coverpage: true
  }
</script>
<script src="//unpkg.com/docsify/lib/docsify.min.js"></script>
```

```JavaScript 
using Abp.Authorization;
using Abp.Authorization.Users;
using Abp.Configuration;
using Abp.Configuration.Startup;
using Abp.Dependency;
using Abp.Domain.Repositories;
using Abp.Domain.Uow;
using Abp.Zero.Configuration;
using Microsoft.AspNetCore.Identity;
using TianDaoFrame.Authorization.Roles;
using TianDaoFrame.Authorization.Users;
using TianDaoFrame.MultiTenancy;

namespace TianDaoFrame.Authorization
{
    public class LogInManager : AbpLogInManager<Tenant, Role, User>
    {
        public LogInManager(
            UserManager userManager, 
            IMultiTenancyConfig multiTenancyConfig, 
            IRepository<Tenant> tenantRepository, 
            IUnitOfWorkManager unitOfWorkManager, 
            ISettingManager settingManager, 
            IRepository<UserLoginAttempt, long> userLoginAttemptRepository, 
            IUserManagementConfig userManagementConfig, 
            IIocResolver iocResolver, 
            RoleManager roleManager,
            IPasswordHasher<User> passwordHasher,
            UserClaimsPrincipalFactory claimsPrincipalFactory)
            : base(
                  userManager, 
                  multiTenancyConfig, 
                  tenantRepository, 
                  unitOfWorkManager, 
                  settingManager, 
                  userLoginAttemptRepository, 
                  userManagementConfig, 
                  iocResolver, 
                  passwordHasher,
                  roleManager,
                  claimsPrincipalFactory)
        {

        }
    }
}
```

```markdown
<!-- _coverpage.md -->
```

![logo](_media/icon.svg)

# docsify <small>3.5</small>

[视频文件加入](../_media/auto.mp4 ':include :type=mp4 width=500px height=500px ')
=======
# huaqyun
华秦云
>>>>>>> b6022c5114baa5b938610e039dbc0a354ed090d6
