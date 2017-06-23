Doctrine Driver for OCI8 and Oracle Database in French
=====

Installation
---

```composer require wizad/doctrine-oci8-french-driver-bundle```

Enable the bundle
---

```php
// app/AppKernel.php
class AppKernel extends Kernel
{
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new Wizad\DoctrineOci8FrenchDriverBundle\WizadDoctrineOci8FrenchDriverBundle(),
        );

        // ...
    }
}
```

Use the driver
---

```yaml
# app/config/config.yml
doctrine:
    dbal:
        driver_class: Wizad\DoctrineOci8FrenchDriver\Doctrine\Driver\OracleFrench
```