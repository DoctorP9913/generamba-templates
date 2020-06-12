
<p>
<details>
<summary>If you don't already have Generamba installed in your project directory, follow this step first</summary>

## Install Generamba

You can find the actual Generamba documentation at https://github.com/strongself/Generamba

1. Make sure your Ruby version is Ruby 2.2 or later.
   >$ ruby --version
2. Run the command `gem install generamba`.

</details>
</p>

## Install Templates

1. Run `generamba setup` in the project root folder.  
2. Open the **Rambafile**.
3. In the *templates:* section, add the name and the directory of the template.
>**Example:**`- {name: remote_template_name, local: 'absolute/file/path'}`
4. Run `generamba template install`
5. Run `generamba gen [MODULE_NAME] [TEMPLATE_NAME]`
6. **Profit**
