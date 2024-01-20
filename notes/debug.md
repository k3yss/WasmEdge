### Instance 1
````
     case OpCode::V128__load8x8_u:
        compileVectorLoadOp(Instr.getTargetIndex(), Instr.getMemoryOffset(),
                            Instr.getMemoryAlign(),
                            LLVM::Type::getVectorType(Context.Int8Ty, 8),Context.Int16x8Ty, false);
`````

### Instance 2 
````
    case OpCode::V128__load8x8_u:
      return runLoadExpandOp<uint8_t, uint16_t>(
          StackMgr, *getMemInstByIdx(StackMgr, Instr.getTargetIndex()), Instr);
````

### Instance 3

  case OpCode::V128__load8x8_u:


### Instance 4 

exi
