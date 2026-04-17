# របៀបបង្កើត Account GitHub និង GitLab

ឯកសារនេះបង្ហាញពីជំហានបង្កើត Account លើ GitHub និង GitLab សម្រាប់អ្នកចាប់ផ្តើម។

## 1) បង្កើត Account GitHub

1. ចូលទៅកាន់ https://github.com/signup
2. បញ្ចូល Email, Password និង Username
3. បំពេញការផ្ទៀងផ្ទាត់ (verification/captcha) តាមដែលប្រព័ន្ធស្នើ
4. ចុច Create account
5. បើកអ៊ីមែលរបស់អ្នក ហើយចុច Verify email ដើម្បីបញ្ចប់ការចុះឈ្មោះ

## 2) បង្កើត Account GitLab

1. ចូលទៅកាន់ https://gitlab.com/users/sign_up
2. បញ្ចូល Name, Username, Email និង Password
3. ចុច Register
4. បើកអ៊ីមែលរបស់អ្នក ហើយ Verify account
5. Sign in ចូលប្រើ GitLab

## 3) ជំហានសំខាន់បន្ទាប់ពីបង្កើត Account

1. បើក Two-Factor Authentication (2FA) សម្រាប់សុវត្ថិភាព
2. បន្ថែម Profile photo និងព័ត៌មានមូលដ្ឋាន
3. បង្កើត SSH key នៅលើម៉ាស៊ីនរបស់អ្នក
4. បន្ថែម SSH public key ទៅ GitHub/GitLab
5. សាកល្បង Clone repository មួយ ដើម្បីពិនិត្យការភ្ជាប់

## 4) បញ្ជាក់ Git local identity

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global --list
```
