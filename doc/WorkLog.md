# WorkLog

---

## 22 March 2019

### **Req_4**: + cmd to display "Current task is unfinished" in warning-msg

same as Req_3 except for usage of `showWarningMessage()` in lieu of `showInformationMessage()`

### **Req_3**: + cmd to display current-time in info-msg

#### Tasks


| File           | Section                | Highlight Point    |            Action            | Details                   |                                     |
| -------------- | ---------------------- | ------------------ | :--------------------------: | ------------------------- | ----------------------------------- |
| `package.json` | `activationEvents`     | Activation Event   |       **Registration**       | `"extension.showTime"`    | to activate your extn               |
| `package.json` | `contributes.commands` | Contribution Point |         **Binding**          | `"extension.showTime"`    | to Command Palette Name "Show Time" |
| `extension.ts` | `activate`             |                    | **Implementation + Binding** | `"extension.showTime"`    | to `f(n)` implementation            |
| `extension.ts` | `activate`             |                    |         **Disposal**         | cmd when extn deactivates |

---

## 21 March 2019

- [vsCode API Documentation](https://code.visualstudio.com/api/get-started/your-first-extension)
- Create scaffolding `yo code`
- Create [git repo](https://github.com/AviralGarg1993/myFirstExtension)

### **Req_1**: info msg `Hello World` -> `Hello! I am Gideon.`

### **Req_2** : cmd title `Hello World` -> `Show Welcome Command`
