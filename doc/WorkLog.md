# WorkLog

---

## 22 March 2019

### **Req_3**: + **cmd** to display current-time in info-msg

|   #   | Tasks                      | File           | Section            | Purpose                           |
| :---: | -------------------------- | -------------- | ------------------ | --------------------------------- |
|   1   | Declare Activation Event   | `package.json` | `activationEvents` | activate extn when cmd is run     |
|   2   | Declare Contribution Point | `package.json` | `contributes`      | show cmd in Command Pallete       |
|   3   | Register & implement       | `extension.ts` | `activate`         | implementation                    |
|   4   | Dispose                    | `extension.ts` | `activate`         | dispose cmd when extn deactivates |

---

## 21 March 2019

- [vsCode API Documentation](https://code.visualstudio.com/api/get-started/your-first-extension)
- Create scaffolding `yo code`
- Create [git repo](https://github.com/AviralGarg1993/myFirstExtension)

### **Req_1**: info msg `Hello World` -> `Hello! I am Gideon.`

### **Req_2** : cmd title `Hello World` -> `Show Welcome Command`