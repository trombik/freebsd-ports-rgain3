PORTNAME=	rgain3
DISTVERSION=	1.1.1
CATEGORIES=	audio python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	y@trombik.org
COMMENT=	Modules to read and write ReplayGain

LICENSE=	GPLv2
LICENSE_FILE=	${WRKSRC}/COPYING

USES=		python
USE_PYTHON=	autoplist distutils

BUILD_DEPENDS=	\
	gstreamer1-plugins-base>0:multimedia/gstreamer1-plugins-base \
	gstreamer1-plugins-good>0:multimedia/gstreamer1-plugins-good \
	gstreamer1-plugins-bad>0:multimedia/gstreamer1-plugins-bad \
	gstreamer1-plugins-ugly>0:multimedia/gstreamer1-plugins-ugly \
	${PYTHON_PKGNAMEPREFIX}gobject3>0:devel/py-gobject3@${PY_FLAVOR}

.include <bsd.port.mk>
