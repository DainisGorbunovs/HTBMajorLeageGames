# HTBMajorLeagueGames
2) In Java:
public class Triple<Integer, Integer, Double> {
  public Triple(Integer requiredFirst) {
    first = requiredFirst;
  }
}
An exception has occurred in the compiler (1.7.0_21). Please file a bug at the Java Developer Connection (http://java.sun.com/webapps/bugreport)  after checking the Bug Parade for duplicates. Include your program and the following diagnostic in your report.  Thank you.
java.lang.NullPointerException
        at com.sun.tools.javac.comp.MemberEnter.baseEnv(MemberEnter.java:1046)
        at com.sun.tools.javac.comp.MemberEnter.complete(MemberEnter.java:880)
        at com.sun.tools.javac.code.Symbol.complete(Symbol.java:421)
        at com.sun.tools.javac.code.Symbol$ClassSymbol.complete(Symbol.java:821)
        at com.sun.tools.javac.code.Symbol$ClassSymbol.flags(Symbol.java:764)
        at com.sun.tools.javac.code.Symbol$ClassSymbol.getKind(Symbol.java:860)
        at com.sun.tools.javac.code.Kinds.kindName(Kinds.java:146)
        at com.sun.tools.javac.comp.Check.duplicateError(Check.java:316)
        at com.sun.tools.javac.comp.Check.checkUnique(Check.java:2672)
        at com.sun.tools.javac.comp.Enter.visitTypeParameter(Enter.java:452)
        at com.sun.tools.javac.tree.JCTree$JCTypeParameter.accept(JCTree.java:1924)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:258)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:272)
        at com.sun.tools.javac.comp.Enter.visitClassDef(Enter.java:416)
        at com.sun.tools.javac.tree.JCTree$JCClassDecl.accept(JCTree.java:591)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:258)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:272)
        at com.sun.tools.javac.comp.Enter.visitTopLevel(Enter.java:332)
        at com.sun.tools.javac.tree.JCTree$JCCompilationUnit.accept(JCTree.java:459)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:258)
        at com.sun.tools.javac.comp.Enter.classEnter(Enter.java:272)
        at com.sun.tools.javac.comp.Enter.complete(Enter.java:484)
        at com.sun.tools.javac.comp.Enter.main(Enter.java:469)
        at com.sun.tools.javac.main.JavaCompiler.enterTrees(JavaCompiler.java:929)
        at com.sun.tools.javac.main.JavaCompiler.compile(JavaCompiler.java:824)
        at com.sun.tools.javac.main.Main.compile(Main.java:439)
        at com.sun.tools.javac.main.Main.compile(Main.java:353)
        at com.sun.tools.javac.main.Main.compile(Main.java:342)
        at com.sun.tools.javac.main.Main.compile(Main.java:333)
        at com.sun.tools.javac.Main.compile(Main.java:76)
        at com.sun.tools.javac.Main.main(Main.java:61)
