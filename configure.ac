AC_INIT(
    [menda-theme],
    [20151214],
    [https://github.com/manjaro/artwork-menda/issues],
    [arc-theme],
    [https://github.com/manjaro/artwork-menda],
    []
)

AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([foreign])
AC_PROG_MKDIR_P

MENDA_ENABLE([LIGHT],         [light],         [Menda Light],   [disable])
MENDA_ENABLE([DARKER],        [darker],        [Menda Darker],  [disable])
MENDA_ENABLE([DARK],          [dark],          [Menda Dark],    [disable])
MENDA_ENABLE([CINNAMON],      [cinnamon],      [Cinnamon],      [disable])
MENDA_ENABLE([GNOME_SHELL],   [gnome-shell],   [GNOME Shell],   [disable])
MENDA_ENABLE([GTK2],          [gtk2],          [GTK2],          [disable])
MENDA_ENABLE([GTK3],          [gtk3],          [GTK3],          [disable])
MENDA_ENABLE([METACITY],      [metacity],      [Metacity],      [disable])
MENDA_ENABLE([UNITY],         [unity],         [Unity],         [disable])
MENDA_ENABLE([XFWM],          [xfwm],          [XFWM],          [disable])
MENDA_ENABLE([XFCE_NOTIFY],   [xfce-notify],   [XFCE Notify],   [disable])
MENDA_ENABLE([TRANSPARENCY],  [transparency],  [transparency],  [disable])

MENDA_GNOME

AC_CONFIG_FILES([
    common/Makefile
    Makefile
])

AC_OUTPUT
